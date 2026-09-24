# MATE Lab Website

배재대학교 학생 개발·창업 동아리 **MATE Lab**의 공식 랜딩페이지입니다.

## 소개

MATE는 **Make · Apply · Try · Evolve.**의 약자입니다. Web, App, AI·Data, IoT·Robotics, UI·UX, Startup 분야에서 아이디어를 실제 프로젝트로 만드는 학생 커뮤니티입니다.

## 프로젝트

- MATE TOEIC 2.0
- MATE Portfolio
- MATE Campus
- MATE Smart Garden

## 로컬에서 확인하기

별도 설치나 빌드가 필요 없는 정적 웹사이트입니다. 저장소를 내려받은 뒤 `dist/index.html`을 브라우저에서 열면 됩니다. 로컬 서버를 사용한다면 저장소 루트에서 다음을 실행하세요.

```bash
npx serve dist
```

또는 VS Code의 Live Server 확장을 사용할 수 있습니다.

## GitHub Pages 배포

이 프로젝트에는 GitHub Pages 자동 배포 설정이 포함되어 있습니다.

1. GitHub 저장소의 **Settings → Pages**로 이동합니다.
2. **Build and deployment → Source**를 **GitHub Actions**로 선택합니다.
3. `main` 브랜치에 푸시하면 자동으로 배포됩니다.
4. 배포 주소는 `https://<github-username>.github.io/mate-lab-website/` 형식입니다.

## 수정해야 할 항목

- `index.html`의 `matelab@example.com`을 공식 문의 이메일로 변경
- 필요 시 인스타그램/GitHub 링크 추가
- 실제 모집 일정과 활동 사진이 준비되면 콘텐츠 업데이트

## 폴더 구조

```text
mate-lab-website/
├── .github/workflows/deploy.yml  # GitHub Pages 자동 배포
├── dist/                          # 바로 배포 가능한 정적 사이트
│   ├── assets/
│   │   ├── favicon.svg           # 브라우저 아이콘
│   │   └── logo.svg              # MATE 로고
│   ├── index.html                # 페이지 콘텐츠
│   ├── styles.css                # 반응형 디자인
│   ├── script.js                 # 메뉴 및 스크롤 애니메이션
│   ├── robots.txt                # 검색엔진 수집 규칙
│   └── sitemap.xml               # 검색엔진 사이트맵
├── .gitignore
├── LICENSE
└── README.md
```

## 기술

HTML5 · CSS3 · Vanilla JavaScript — 프레임워크와 외부 의존성 없이 빠르게 동작합니다.

## 라이선스

MIT License
