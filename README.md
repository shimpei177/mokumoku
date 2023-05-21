# README

## 環境構築
```
$ bundle install --without=production
$ bin/rails db:setup
$ yarn install
$ bin/webpack
$ bin/rails s
```

## 事業をエンジニアリングしよう提案編の回答は以下に記述してください
選択した事業側の課題
・サービス登録者数の内、男性60%に対して、女性は40%。一方で、サービス内のもくもく会に参加した人の比率は、男性90%：女性10%と大きな差が出ています。もっと女性が使いやすいようなサービス設計にする必要があるのではないか？

提案内容
・女性限定のもくもく会を開けるようにする
・Contentにガイドをつけて詳細が分かり易くかけるようにする
・もくもく会のレビューができるようにする。

実装方針
・女性限定のもくもく会を開けるようにする
→男女による参加の権限をユーザーに与える
・Contentにガイドをつけて詳細が分かり易く書けるようにする
→薄い字でガイドを打ち込んでおく
・もくもく会のレビュができるようにする
→コメント機能を設ける
