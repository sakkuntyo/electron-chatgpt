chatgpt に聞いて作成
https://chatgpt.com/share/6877ad5f-9e3c-8013-8ea0-e4b8b682039b

# 概要
- nodejs 18.15 で動作確認。
- package.json は index.js -> main.js へ変更する以外に変更していません。
- npm install したパッケージは npx で使用する必要がありました。

# メモ
- 動作確認
  - ```npx electron .```
- パッケージング
  - ```npx electron-packager . chatgpt-client --platform=win32 --arch=x64 --icon=icon.ico --overwrite```
