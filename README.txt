WEB — 독립 실행형 웹앱(PWA)

[GitHub Pages 배포]
1. 이 압축 파일을 풉니다.
2. WEB_PWA 폴더 안의 파일들을 GitHub 저장소의 루트에 그대로 업로드합니다.
   index.html / manifest.webmanifest / sw.js / icons 폴더가 같은 위치에 있어야 합니다.
3. GitHub 저장소 → Settings → Pages
4. Build and deployment에서 Deploy from a branch를 선택합니다.
5. Branch를 main, 폴더를 /(root)로 선택하고 Save 합니다.
6. 생성된 GitHub Pages 주소로 접속합니다.

[앱 설치]
Android/Chrome:
- GitHub Pages 주소 접속 → 브라우저 메뉴 → '앱 설치' 또는 '홈 화면에 추가'

iPhone/Safari:
- GitHub Pages 주소 접속 → 공유 버튼 → '홈 화면에 추가'
- iOS에서는 브라우저 버전에 따라 PWA 동작 방식에 차이가 있을 수 있습니다.

PC/Chrome 또는 Edge:
- GitHub Pages 주소 접속 → 주소창의 설치 아이콘 또는 브라우저 메뉴 → 앱 설치

[데이터]
- 기존 WEB 프로그램과 마찬가지로 작품 데이터는 브라우저의 로컬 저장소를 사용합니다.
- 다른 기기/다른 브라우저로 데이터가 자동 동기화되지는 않습니다.
- 기기를 바꾸거나 브라우저 데이터를 삭제하기 전에는 프로그램의 백업 기능으로 백업 파일을 보관하세요.
- GitHub에 프로그램 파일을 올린다고 작품 데이터가 GitHub에 업로드되는 것은 아닙니다.

[파일]
index.html            WEB 본체
manifest.webmanifest  앱 설치 정보
sw.js                 오프라인 캐시
icons/                앱 아이콘
README.txt             이 설명서
