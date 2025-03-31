# Flutter

## 目次
- [フォルダ構成](##フォルダ構成)
- [Flutter memo](#flutter-memo)
- [Widget](#Widget)

## フォルダ構成

- 各プラットフォーム
  - android/
  - ios/
  - linux/
  - macos/
  - web/
  - windows/

- 共通
  - lib/
  - test/
  - pubspec.yaml

## Flutter memo
Flutter Widgetというパーツの組み合わせで構築する

## Widget
child: 単一の子要素を持つ
children: 複数の子要素を持つ

- Column
Widgetを縦に並べる(行にする)
- Row
Widgetを横に並べる(列にする)
- TextButton
  - onPressed: ボタンが押された時のイベントを設定
- FloatingActionButton
画面右下最前面に表示されるボタン
- drawer
画面左側サイドメニュー
- endDrawer
画面右側サイドメニュー

## Stateful / Stateless
Stateful: 状態を持ち、状態の変化を覚えている.動的で変化
Stateless: 状態を持たずに常に同じ状態.静的で変化しない

mainAxisAlignment: MainAxisAligment.spaceAround
[https://qiita.com/ikemura23/items/67af19b6cbf16fb0251a](https://qiita.com/ikemura23/items/67af19b6cbf16fb0251a)

## Icons
[Icons一覧](https://api.flutter.dev/flutter/material/Icons-class.html)