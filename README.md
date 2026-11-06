# musical-otk.github.io

관극 다이어리 통합 저장소. 새 작품은 저장소를 새로 만들지 않고 여기에 폴더로 추가한다.
기존 작품(저장소별)은 그대로 두며, 같은 이름의 저장소가 있으면 그 주소는 저장소가 차지한다.

- `apps.json` — 허브(otk-schedule)가 읽는 폴더 목록
  - `{ "path": "ever2026/" }` — 작품 앱 (manifest·index.html 에서 이름·색·기록 키를 읽는다)
  - `{ "path": "extras/hwinter2026.json", "app": false }` — 앱 없는 기타 공연(콘서트 등). `extras/` 에 공연마다 파일 하나
    (`name`·`icon`·`venue`·`price`·`url` + `schedule` 배열 — 회차마다 `cast1`, `cast2` …)
- `index.html` — 지금은 허브로 넘기기만 한다
