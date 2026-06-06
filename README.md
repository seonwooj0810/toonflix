# toonflix

Flutter 학습용 프로젝트입니다. 노마드 코더 Flutter 강의를 따라 만든 정적 UI 클론으로, 현재는 지갑/금융 대시보드 형태의 단일 화면을 구현하고 있습니다.

> 저장소 이름은 "toonflix"이지만, 현 시점 코드는 웹툰 관련 기능이 아니라 지갑(잔액/Transfer/Request/Wallets) UI 화면입니다. 강의 초반 레이아웃 실습 단계로 보입니다.

## 구현 내용

- `lib/main.dart` — 잔액(Total Balance), Transfer/Request 버튼, Wallets 목록으로 구성된 단일 `Scaffold` 화면
- `lib/widgets/button.dart` — 색상/텍스트를 받는 재사용 가능한 둥근 `Button` 위젯

## 기술 스택

- Flutter (Dart, SDK `>=3.4.3 <4.0.0`)
- 의존성: `cupertino_icons`만 사용 (네트워킹/상태관리 라이브러리 없음, 정적 화면)

## 실행

```bash
flutter pub get
flutter run
```

> 저장소 주 언어가 GitHub에서 C++로 표기되는 것은 Flutter 데스크톱 네이티브 빌드 파일(`windows/`, `linux/`, `macos/`) 때문이며, 실제 애플리케이션 코드는 Dart입니다.
