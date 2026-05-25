# PARK YIHYUN — Portfolio v2

UI·UX 디자이너 박이현(Park Yihyun)의 포트폴리오 — 버전 2.

- **index.html** — 랜딩 페이지 (About · Works · Contact)
- **portfolio-details.html** — 6개 프로젝트 상세 (탭 기반 뷰어)

## 디자인 시스템

- **컬러**: 코발트 #2563EB (포인트), #0C0C0C (다크), #FFFFFF (베이스)
- **타이포**: Pretendard Variable
- **레이아웃**: max-width 1200px, 다크 히어로 + 화이트 본문, 에디토리얼 그리드
- **반응형**: 1024 / 768 / 480 / 360 breakpoints

## 구조

```
portfolio-v2/
├── index.html              랜딩 (Hero · About · Works · Contact)
├── portfolio-details.html  프로젝트 상세 (work-1 ~ work-6 탭)
└── README.md
```

## 로컬 확인

```bash
npx http-server -p 5502 -c-1
```

브라우저에서 `http://localhost:5502` 열기.

## 배포

GitHub Pages를 통해 배포. `main` 브랜치 루트가 정적 호스팅 대상.

---

© 2026 PARK YIHYUN. All artworks shown are personal documentation of professional work.
