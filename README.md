# てをあげくん Windows 版（配布）

「てをあげくん」Windows 版のインストーラーと、自動更新のファイルを置く場所です。ソースコードは置いていません。

## 入れ方

1. PC の種類を確かめる: 設定 →「システム」→「バージョン情報」の「システムの種類」
2. インストーラーをダウンロードする
   - 「x64 ベース プロセッサ」の PC: [TeoageKun-win-x64-Setup.exe](https://github.com/philiaxis/teoage-kun-windows-releases/releases/latest/download/TeoageKun-win-x64-Setup.exe)
   - 「ARM ベース プロセッサ」の PC: [TeoageKun-win-arm64-Setup.exe](https://github.com/philiaxis/teoage-kun-windows-releases/releases/latest/download/TeoageKun-win-arm64-Setup.exe)
3. ダウンロードしたファイルを開く（その PC を使う職員の Windows のアカウントで。管理者として開かない）
4. 「Windows によって PC が保護されました」と出たら、「詳細情報」→「実行」を押す（いまはインストーラーに署名していないため）
5. 数十秒で入り、「てをあげくん」が起動する。Web 版と同じメールアドレスとパスワードでログインする

- 管理者の権限は要りません。入れる場所は、PC の利用者ごとの `%LOCALAPPDATA%\TeoageKun` です
- 新しい版は自動で入ります（起動したときと、約 4 時間ごとに確かめます）
- 動く OS: Windows 10 2004 以降・Windows 11（x64・ARM64）
- 「スマート アプリ コントロール」がオンの Windows 11 の PC には、署名ができるまで入れられません
- わからないことは、施設の管理者に問い合わせてください

## 版の一覧

[Releases](https://github.com/philiaxis/teoage-kun-windows-releases/releases) を見てください。
