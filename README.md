# 테니스판타지 (TENNIS FANTASY) — 공식 안내 홈페이지

서울 서초·강남·동작의 실내 테니스 레슨 & 클럽, **테니스판타지**의 공식 안내 페이지입니다.
반포점 · 방배점 · 삼성점 · 동작테니스장의 시설, 레슨·수강료, 성장 로드맵, 이벤트·클럽, 오시는 길을 한 페이지에 담았습니다.

- 공개 주소: https://ouy2006.github.io/tf-homepage/
- 구성: 빌드 과정 없는 정적 페이지 (`index.html` 1장 + `images/` + `fonts/`)
- 폰트: Spoqa Han Sans Neo, Syne — 외부 CDN 없이 `fonts/` 에 자체 호스팅
- 이미지·폰트 경로는 모두 상대경로라 `index.html` 을 파일로 열어도 그대로 보입니다.

## 수정

- 색·서체: `index.html` 의 `:root` 토큰과 `@font-face`
- 가격표: `<table class="prices">` 블록
- 사진: `images/` 의 같은 파일명으로 덮어쓰기 (권장 1600~1800px 폭, JPEG)

`main` 브랜치에 푸시하면 GitHub Pages 에 바로 반영됩니다.
