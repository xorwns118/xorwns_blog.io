# xorwns_blog.io

신입 개발자 포트폴리오를 보여주기 위한 정적 GitHub Pages 블로그입니다.

## 구조

```text
.
├── index.html
├── assets/
│   └── css/
│       └── style.css
├── projects/
│   ├── project-01.html
│   ├── project-02.html
│   └── project-03.html
└── Image/
    ├── project-01/
    │   ├── thumbnail.svg
    │   └── detail-01.svg
    ├── project-02/
    │   ├── thumbnail.svg
    │   └── detail-01.svg
    └── project-03/
        ├── thumbnail.svg
        └── detail-01.svg
```

## 수정 방법

- 메인 목록의 프로젝트 제목, 기간, 날짜는 `index.html`에서 수정합니다.
- 각 상세 페이지 내용은 `projects/project-XX.html`에서 수정합니다.
- 썸네일 이미지는 `Image/project-XX/thumbnail.svg`를 원하는 이미지 파일로 교체한 뒤 `index.html`의 `img src` 경로를 맞춥니다.
- 프로젝트별 추가 이미지는 `Image/project-XX/` 폴더 안에 넣고 상세 HTML에서 이미지 경로를 추가합니다.
