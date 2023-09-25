#  「日欧DHクロストーク」のページ

サイトはJekyllを使ってます。

コンテンツを追加する場合は、
[ここ](https://docs.github.com/ja/pages/setting-up-a-github-pages-site-with-jekyll/adding-content-to-your-github-pages-site-using-jekyll)とかを参照してください。

## Theme
Themeには[slate](https://github.com/pages-themes/slate)を使っています。

## ローカル環境でサイトを開発したり、サイトをチェックしてみたい時
- Git cloneでこのリポジトリをローカルにクローン
- Jekyllをインストールして
- 次のコマンドを入力

```
$ cd session1 
$ cd docs
$ bundle install
[$ bundle add webrick] # 次のコマンドでエラーが発生した場合（MacOSでHomebrewを使ってると起きるかも）
$ bundle exec jekyll serve 
```
