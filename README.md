# 타임 디펜더스 웹사이트 (Time Defenders)

정적 사이트 — 빌드 없음. `index.html` 하나가 한국어·English·日本語를 모두 그린다
(브라우저 언어로 자동 선택, 상단 버튼으로 전환, `?lang=en` 링크 가능).
`index-en.html` / `index-ja.html`은 기존 주소를 살리려는 리다이렉트다 (utm 등 쿼리 유지).

## 다운로드 링크 (광고·SNS 프로필용)
`https://nini-universe.github.io/time-defenders-website/download/`
- 아이폰·아이패드 → App Store, 안드로이드 → Google Play로 자동 이동
- PC → 자동 이동 없이 버튼만
- 메인 소개 페이지는 자동 이동하지 않는다 — 폰에서도 소개를 볼 수 있게

## 그림 출처 (게임 저장소 `time_dependers`, 2.0 전면 개편)
- 아이콘: `ios/Runner/Assets.xcassets/AppIcon.appiconset/Icon-App-1024x1024@1x.png` → `app_icon.png`, `img/icon.webp`, `favicon.png`, `apple-touch-icon.png`
- 키 아트: `output/design/store-shots/art/key_*.png` → `img/art/`
- 스크린샷: `store_listing/screenshots/appstore_iphone/{ko,en,ja}/` → `img/shots/` (폭 600 webp)
- 시대·맵·무기·계급장·UI: `assets/images/{battle,enhance,main,ranks}/` → `img/eras`, `img/weapons`, `img/ranks/{ko=rok_army,en=us_army,ja=japan}`, `img/ui`
- OG 이미지: `store_listing/screenshots/googleplay_feature/ko.png` → `img/og.jpg`
- 문구: `store_listing/APPSTORE_2.0.0.md`, 무기·계급 이름은 `lib/l10n/locales/*.dart`
