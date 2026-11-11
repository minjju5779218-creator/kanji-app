# 한자 연습장 웹앱 (아이패드용)

이 폴더의 파일 6개를 GitHub Pages에 올리면, 아이패드 홈 화면에 설치해서 쓰는 앱이 됩니다.

- index.html — 앱 본체 (한자 1,026자 데이터 포함)
- manifest.webmanifest — 앱 이름·아이콘 설정
- sw.js — 인터넷 없이도 열리게 해 주는 파일
- icon-192.png, icon-512.png, apple-touch-icon.png — 아이콘

## 올리는 방법 (무료)
1. github.com 에서 회원가입
2. 오른쪽 위 + → New repository → 이름 `kanji-app`, Public 선택 → Create repository
3. "uploading an existing file" 클릭 → 위 6개 파일 선택 → Commit changes
4. Settings → Pages → Branch: `main`, 폴더 `/ (root)` → Save
5. 1~2분 뒤 `https://내아이디.github.io/kanji-app/` 주소가 생김

## 아이패드에 설치
Safari로 위 주소 열기 → 공유 버튼 → 홈 화면에 추가

## 나중에 앱을 고쳤을 때
고친 index.html을 같은 저장소에 다시 올리고, sw.js 안의 `kanji-v1`을 `kanji-v2`처럼 숫자를 올려서 함께 올리면 아이패드에 새 버전이 반영됩니다.
