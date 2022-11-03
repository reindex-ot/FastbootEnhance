# Fastboot Enhance JP (非公式日本語版ビルド)

![A user-friendly **Fastboot ToolBox** & **Payload Dumper** for Windows](screenshots/Banner.png)

<img src="screenshots/ss1.png" width="400" height="300" /> <img src="screenshots/ss2.png" width="400" height="300" />
<img src="screenshots/ss3.png" width="400" height="300" /> <img src="screenshots/ss4.png" width="400" height="300" />

## 何ができるんですか?

- fastboot上でバージョンの表示
- fastbootd、bootloader、recoveryとsystemの起動
- A/Bスロットの切り替え
- **FastbootdでPayload.binを書き込む機能**
- イメージの書き込み
- パーティションの消去
- 論理パーティションの削除
- 論理パーティションの作成
- 論理パーティションのリサイズ
- Payload.binの展開
- **Payload.binから特定のイメージを抽出**
- Payloadのバージョンを表示
- 動的パーティションのメタデータを表示

## 使用方法

- `.NET Framework 4.8以降` がインストール済みである事

- `FastbootEnhance_jp.zip`を[GitHub Releases](https://github.com/reindex-ot/FastbootEnhance_jp/releases)からダウンロード
- Zipファイルを展開
- `FastbootEnhance.exe`を実行

## 注意事項

- インクリメンタルパッケージには非対応です。

(かなり使い勝手が悪いので対応する予定はなし)

- しかしチェックサムが通るのであれば、インクリメンタルパッケージからイメージの抽出は可能です。

(チェックサムを無視するにチェックを入れてない場合はチェックサムを行ないます)

## ビルド環境

- Visual Studio 2022を使用しています

## クレジット

- [Android Platform Tools](https://developer.android.com/studio/releases/platform-tools)
- [DotNetZip](https://github.com/haf/DotNetZip.Semverd)
- [Protobuf](https://github.com/protocolbuffers/protobuf)
- [XZ.NET](https://github.com/RomanBelkov/XZ.NET)
