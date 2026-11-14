# GitHub Pages 배포

저장소에 연결한 뒤 `main` 또는 `master` 브랜치에 push하면 GitHub Actions가 책벗 사이트를 GitHub Pages에 배포합니다. 이 워크플로는 `index.html`과 `data/books.js`만 공개 사이트 아티팩트에 포함합니다.

첫 배포 전에 저장소 Settings → Pages → Build and deployment에서 Source를 GitHub Actions로 설정해야 할 수 있습니다. 배포가 완료되면 Actions의 `Publish book curation site` 실행 결과에 공개 페이지 URL이 표시됩니다. 일반적인 프로젝트 저장소 URL은 `https://<계정>.github.io/<저장소>/` 형식입니다.
