# Deutsch Lernen — 독일어 단어장

## 포함 기능
- 플래시카드: 독일어→한국어 / 한국어→독일어
- 품사별 필터
- 혼합·방향별·관사 시험
- 오답 노트와 알고 있는 단어 표시
- 일일 목표와 오늘 학습 수
- 브라우저 localStorage 자동 저장
- 학습 기록 JSON 내보내기
- PWA 설정과 서비스 워커(호스팅 후 지원 브라우저에서 설치/캐시)

## 파일
- `index.html`: 사이트 본체
- `manifest.webmanifest`: 홈 화면 설치 설정
- `sw.js`: 캐시/오프라인 기본 지원
- `icon.svg`: 아이콘

## 인터넷에 무료로 공개하는 쉬운 방법 (GitHub Pages)
1. GitHub 계정으로 로그인하고 새 저장소(repository)를 만듭니다. 예: `deutsch-lernen`
2. 이 ZIP의 파일 4개를 저장소 최상위에 업로드합니다.
3. 저장소의 Settings → Pages로 들어갑니다.
4. Build and deployment에서 Deploy from a branch를 선택합니다.
5. Branch를 `main`, 폴더를 `/ (root)`로 지정하고 Save를 누릅니다.
6. 몇 분 뒤 표시되는 `https://사용자이름.github.io/deutsch-lernen/` 주소로 사이트를 엽니다.
7. Android Chrome에서 해당 주소를 열고 `⋮` → `홈 화면에 추가` 또는 `앱 설치`를 누릅니다.

메뉴 명칭은 GitHub/Chrome 버전에 따라 조금 다를 수 있습니다.

## 주의
- 학습 기록은 서버 계정이 아니라 해당 기기의 브라우저 localStorage에 저장됩니다.
- 다른 기기/브라우저와 자동 동기화되지 않습니다. `학습 기록 내보내기`로 JSON 백업을 만들 수 있습니다.
- 브라우저 데이터를 삭제하면 기록이 사라질 수 있습니다.
- 설치 및 오프라인 동작은 브라우저/호스팅 환경에 따라 달라질 수 있습니다.
- 발음 표기는 한국어식 근사치입니다.
