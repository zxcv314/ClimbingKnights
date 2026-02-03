# ClimbingKnights

Climbing Knights는 물리 법칙을 기반으로 한 하드코어 클라이밍 액션 게임입니다. 
플레이어는 용감한 기사가 되어 마왕성의 꼭대기인 10,000m 정상을 향해 험난한 여정을 떠납니다.
주요 특징
원터치 하드코어 액션: 타이밍에 맞춰 점프하고 홀드를 잡는 단순하지만 깊이 있는 물리 기반 조작.

스토리 모드: 0m부터 10,000m까지, 환경이 판이하게 다른 5개의 구간(Zone)을 돌파하는 여정.

로그인 및 저장 시스템: 기사명을 등록하고 로컬 스토리지를 통해 개인 최고 기록(Best Distance)을 유지.

심화된 홀드 메커니즘: 움직이는 벌레 홀드, 미끄러지는 얼음, 순간이동하는 마법 홀드 등 10가지 타입의 홀드 구현.

장애물 시스템: 낙하하는 바위와 함정 홀드에서 소환되는 치명적인 고블린 등 다양한 위협 요소.

프로젝트 구조 및 에셋 경로
에셋 파일이 정상적으로 로드되려면 아래와 같은 디렉토리 구조를 유지해야 합니다.

Plaintext
project/
├── index.html          # 메인 게임 소스 코드 (HTML5/JS)
├── assets/
│   ├── background/     # bg_basic.png, bg_rock.png, wall.png, ground.png 등
│   ├── effect/         # jump_dust.png, warning_circle.png 등
│   ├── hold/           # hold_normal.png, hold_broken.png, hold_ice.png 등
│   └── player/         # player_idle.png, player_jump_left.png, player_jump_right.png 등
└── README.md
구간(Zone) 진행
Basic Zone (0m ~ 2,000m): 기본적인 조작을 숙달할 수 있는 평범한 돌담 구간.

Rock Zone (2,000m ~ 4,000m): 낙하하는 바위와 좌우/상하로 움직이는 바위벌레 홀드 등장.

Snow Zone (4,000m ~ 6,000m): 매달려도 멈추지 않는 눈벌레와 아래로 미끄러지는 얼음 홀드 배치.

Lava Zone (6,000m ~ 8,000m): 복잡한 궤적의 용암벌레와 주기적으로 사라졌다 나타나는 용암 홀드.

Castle Zone (8,000m ~ 10,000m): 순간이동하는 마법 홀드와 기습적인 고블린 함정이 도사리는 최종장.

조작 방법
홀드 부착 시: 캐릭터 주변의 화살표가 원하는 방향을 가리킬 때 화면을 터치하여 점프합니다.

공중 체류 시: 홀드 근처에 도달하여 녹색 가이드 원이 보일 때 화면을 터치하여 홀드를 붙잡습니다.

주의: 타이밍을 놓쳐 홀드를 잡지 못하거나 장애물에 충돌하면 즉시 게임 오버됩니다.

개발자 정보 (Developer Info)
개발자명: [FrontZero]

개발 연도: 2026년
