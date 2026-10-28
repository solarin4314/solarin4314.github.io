# Jemin Lee | Data Engineer Portfolio

🔗 https://solarin4314.github.io

대규모 로그와 트래픽을 처리하는 데이터 파이프라인과 분석 시스템을 설계·운영해 온 데이터 엔지니어 포트폴리오입니다.
Jekyll로 만들고 GitHub Pages로 배포합니다.

## 내용 수정 위치

| 내용 | 파일 |
| --- | --- |
| 사이트 제목·설명·메뉴 | `_config.yml` |
| 홈 (Hero, Architecture, Featured Projects, Experience 요약) | `_layouts/home.html` |
| 프로젝트 목록 | `_data/projects.yml` |
| 경력 타임라인 | `_data/timeline.yml` |
| Experience / Strengths / Contact 페이지 | `experience.md`, `strengths.md`, `contact.md` |
| 스타일 (라이트/다크 색상 포함) | `assets/css/main.scss` |

- 프로젝트의 `featured: true` 항목이 홈에 최대 3개까지 표시됩니다.
- Strengths 페이지의 "관련 프로젝트"는 `_data/projects.yml`의 `strengths` 값으로 자동 연결됩니다.
- 프로젝트 상세 페이지(케이스 스터디)를 만들면 해당 프로젝트의 `writeup`에 경로를 적어 주세요. 비어 있으면 Projects 페이지의 카드로 연결됩니다.

## 로컬 실행

```bash
bundle install
bundle exec jekyll serve
```

http://localhost:4000 에서 확인할 수 있습니다.

## Credits

- Theme: [devlopr-jekyll](https://github.com/sujaykundu777/devlopr-jekyll) (MIT License, © Sujay Kundu, [LICENSE](LICENSE))
- Icons: [Font Awesome Free 6.5.0](https://fontawesome.com) (`assets/fontawesome-free/LICENSE.txt`)
