# Android Sunflower for Androidテスト全書

[Androidテスト全書](https://peaks.cc/android_testing)(以降では単に本書籍と表記します)の第5章「UIテスト (Espresso編)」のサンプルコードです。

本リポジトリは、
GoogleがAndroid Jetpackのサンプルアプリとして開発している[Android Sunflower](https://github.com/googlesamples/android-sunflower)をフォークしたものです。

Android Sunflower付属の、オリジナルのREADMEは[README.orig.md](README.orig.md)を参照してください。


## 動作確認環境

- Android Studio 3.2 Beta 5
- 言語設定を日本語にしたAndroid 8.0が稼動する端末


## ブランチ

以下のブランチは、本書籍第5章の解説の各ステップと対応しています。
コードを確認しながら第5章を読み進めたいときに活用してください。

- [step1-3](https://github.com/peaks-cc/espresso-test-sample/tree/step1-3)
- [step4](https://github.com/peaks-cc/espresso-test-sample/tree/step4)
- [step5](https://github.com/peaks-cc/espresso-test-sample/tree/step5)
- [step6-7](https://github.com/peaks-cc/espresso-test-sample/tree/step6-7)
- [step8-9](https://github.com/peaks-cc/espresso-test-sample/tree/step8-9)

残りのブランチと、その意味は次の通りです。

- [my-first-recording](https://github.com/peaks-cc/espresso-test-sample/tree/my-first-recording): 
  テストコードが無い状態のものです。
  書籍を参考に、テストを書いてみたい場合は、このブランチから始めてみてください。
- [espresso-test-sample](https://github.com/peaks-cc/espresso-test-sample/tree/espresso-test-sample): 
  GitHubで表示されているデフォルトブランチです。
  [step8-9](https://github.com/peaks-cc/espresso-test-sample/tree/step8-9)
  と同じものです
- [master](https://github.com/peaks-cc/espresso-test-sample/tree/master): 
  フォーク元のmasterブランチです。

## オリジナルのAndroid Sunflowerとの違い

- Android Studio 3.2 Beta 5でビルドできるように、ビルドスクリプトを修正しています。
- 本書籍で紹介しているライブラリを依存関係に追加したり、バージョンを最新化しています。
- `app/src/androidTest`配下のテストコードを全て削除しています。
  代わりに、本書籍のサンプルコード(テストコード)を追加しています。
- オリジナルのREADME.mdのファイル名をREADME.orig.mdにリネームしています。
- `app/src/debug`配下に、独自のGlideモジュールを追加しています。

## ライセンス

Original Copyright 2018 Google, Inc.  
Modifications Copyright 2018 TOYAMA Sumio &lt;jun.nama@gmail.com&gt;  

Licensed under the
[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
