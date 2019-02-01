<<<<<<< HEAD
# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
=======
# railstutorial
https://railstutorial.jp/chapters/beginning?version=5.1

2019/01/29
やっていく

1.1.1演習

1.Ruby on Railsで使うRuby gemはどのWebサイトにありますか？ヒント: 分からないときはとにかくググりましょう。
https://www.ruby-lang.org/ja/libraries/

2.現時点でのRailsの最新バージョンはいくつですか？
2019/01/29時点では5.2.2

3.Ruby on Railsはこれまでに何回ダウンロードされたでしょうか？調べてみてください。
2019/01/29時点では158,941,506回
http://bestgems.org/search?q=rails

1.2
AWSのユーザー登録をした
Cloud9は東京リージョンはサポート外だったので、シンガポールにした
設定補足
https://remonote.jp/aws-cloud9-ruby-on-rails

1.3
rails _5.1.6_ new hello_app
上記コマンドでわーっとファイルとフォルダが作成される
Railsアプリの標準化されたファイル構造

1.3.2演習
1.デフォルトのRailsページに表示されているものと比べて、今の自分のコンピュータにあるRubyのバージョンはいくつになっていますか? コマンドラインでruby -vを実行することで簡単に確認できます。
railsページ：2.5.3 (x86_64-linux)
コマンド：ruby 2.5.3p105

2.同様にして、Railsのバージョンも調べてみましょう。調べたバージョンはリスト 1.1でインストールしたバージョンと一致しているでしょうか?
railsページ：5.1.6.1
コマンド：Rails 5.1.6.1

1.3.4演習
1.リスト 1.7のhelloアクションを書き換え、「hello, world!」の代わりに「hola, mundo!」と表示されるようにしてみましょう。
やった
2.Railsでは「非ASCII文字」もサポートされています。「¡Hola, mundo!」にはスペイン語特有の逆さ感嘆符「¡」が含まれています (図 1.16)18。「¡」文字をMacで表示するには、Optionキーを押しながら1キーを押します。この文字をコピーして自分のエディタに貼り付ける方が早いかもしれません。
やったぜ。
3.リスト 1.7のhelloアクションを参考にして、２つ目のアクションgoodbyeを追加しましょう。このアクションは、「goodbye, world!」というテキストを表示します。リスト 1.9のルーティングを編集して、ルートルーティングの割り当て先をhelloアクションからgoodbyeアクションに変更します (図 1.17)。
やったわ。

1.6.1 本章のまとめ
Ruby on Railsとは、Web開発のためのフレームワークであり、Rubyプログラミング言語によって記述されている。
事前設定済みのクラウド環境を利用することで、Railsのインストール、アプリケーションの生成、生成されたファイルの編集を簡単に行うことができる。
Railsにはrailsという名前のコマンドラインコマンドがあり、rails newで新しいアプリケーションを生成したり、rails serverでローカルサーバーを実行したりできる。
コントローラのアクションを追加したり、ルートルーティングを変更したりするだけで「hello, world」アプリケーションを作成できる。
Gitによるバージョン管理を導入し、Bitbucketの非公開リポジトリにプッシュする理由は、データの喪失を防止し、他の開発者との共同作業を行えるようにするため。
作成したアプリケーションをHerokuの本番環境にデプロイした。
>>>>>>> origin/master
