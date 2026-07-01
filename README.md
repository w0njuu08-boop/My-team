# 체크메이트 (CheckMate)

흩어진 출석체크 링크를 한 곳에 모아 관리하는 개인용 웹앱입니다.

## GitHub Pages로 배포하는 방법

1. GitHub에서 새 저장소(Repository)를 만듭니다. (Public이어야 무료로 Pages 사용 가능)
2. 이 폴더 안의 파일 전부(`index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`)를 저장소에 업로드합니다.
   - 저장소 페이지에서 "Add file" → "Upload files"로 드래그 앤 드롭하면 됩니다.
3. 저장소 메뉴에서 **Settings → Pages**로 들어갑니다.
4. "Build and deployment" 항목에서 Source를 **Deploy from a branch**로 설정하고,
   Branch를 **main / (root)**로 선택한 뒤 저장합니다.
5. 1~2분 정도 기다리면 상단에 `https://[내계정].github.io/[저장소이름]/` 링크가 생깁니다.
6. 그 링크를 휴대폰 브라우저(크롬/사파리)로 열고, 메뉴에서 **"홈 화면에 추가"**를 누르면
   아이콘이 생기고 앱처럼 실행됩니다 (주소창 없이 전체화면으로 열림).

## 데이터 관련
- 모든 데이터는 브라우저(휴대폰)의 로컬 저장소에만 저장됩니다. 서버에 전송되지 않습니다.
- 헤더의 📦 버튼으로 데이터를 JSON 파일로 백업/복원할 수 있습니다.
