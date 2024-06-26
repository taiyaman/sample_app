# Ruby on Rails チュートリアルのサンプルアプリケーション
# test
これは、次の教材で作られたサンプルアプリケーションです。
[*Ruby on Rails チュートリアル*](https://railstutorial.jp/)
（第7版）
[Michael Hartl](https://www.michaelhartl.com/) 著

## ライセンス

[Ruby on Rails チュートリアル](https://railstutorial.jp/)内にある
ソースコードはMITライセンスとBeerwareライセンスのもとで公開されています。
詳細は [LICENSE.md](LICENSE.md) をご覧ください。

## 使い方

このアプリケーションを動かす場合は、まずはリポジトリをフォークしてください。

フォークしたリポジトリで、「Code」から「Codespaces」タブに移動し、
「Create codespace on main」をクリックすると環境構築がスタートします。
Railsサーバーが立ち上がり、シンプルブラウザが表示されるまでしばらくお待ちください。

次に、データベースへのマイグレーションを実行します。

```
$ rails db:migrate
```

最初の起動時にエラーになった際は下記を実行すると解消する

```
$ rvm install 3.2.3
$ bundle install
$ rails s
```

最後に、テストを実行してうまく動いているかどうか確認してください。

```
$ rails test
```

詳しくは、[*Ruby on Rails チュートリアル*](https://railstutorial.jp/)
を参考にしてください。 

##2024/05/06 ch06 プルリクエスト練習
ch06を進めたあと、プルリクエストをする前にmainブランチにマージして、
pushしてしまったため、あらたにブランチを切ってプルリクエストを送る
