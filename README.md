# 메뉴냥

모찌가 메뉴를 골라주는 게임이에요.

## GitHub Pages에 올리기
1. GitHub에서 새 저장소를 만들어요 (예: `menu-nyang`, Public).
2. `index.html`, `menu.json`, `README.md` 를 저장소에 올려요 (Add file → Upload files).
3. Settings → Pages → Branch를 `main` / `/(root)` 로 두고 Save.
4. 1~2분 뒤 `https://<내아이디>.github.io/menu-nyang/` 에서 열려요.

## 호스트로 메뉴 고치기
1. 토큰 만들기: GitHub → Settings → Developer settings → Personal access tokens → Fine-grained tokens → Generate new token
   - Repository access: **Only select repositories** → 이 저장소만
   - Permissions → Repository permissions → **Contents: Read and write**
2. 사이트 주소 끝에 `#host` 를 붙여서 열어요: `https://<내아이디>.github.io/menu-nyang/#host`
3. **host** 버튼 → GitHub 연결 설정에 토큰을 붙여넣어요 (계정, 저장소는 자동으로 채워져요).
4. 메뉴를 고치고 **저장**. 저장소의 `menu.json` 이 바뀌고, 1~2분 뒤 모두에게 반영돼요.

토큰은 그 브라우저에만 저장돼요. 다른 사람에게 토큰을 알려주지 마세요.
`menu.json` 을 GitHub에서 직접 고쳐도 돼요.
