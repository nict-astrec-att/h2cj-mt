# H2CJ-MT (Historical-to-Contemporary-Japanese Machine Translation Data)

自動翻訳システムにより歴史的日本語資料原文を現代日本語に自動翻訳したテキストを公開しています．

### data-20260207

みんなで翻刻 v3 データと同様のディレクトリ構造，資料IDで，原文ファイル `(ID).txt` と訳文ファイル `(ID).txt.trans.txt` を格納しています．

- 翻訳モデル：NICTで研究開発中の多言語・多文化翻訳システムを使用．
- 入力テキスト：「[みんなで翻刻](https://github.com/yuta1984/honkoku-data/tree/master/v3)」v3 データの原文（翻刻）テキスト．原文テキストを資料（書籍）単位で連結したものを使用しています．
- 翻訳の方法：翻訳モデルにより，原文のパラグラフ単位への自動分割と訳文テキスト生成を実行しています．
- 出力データ形式：原文パラグラフと訳文パラグラフが `<Paragraph><SOURCE>...</SOURCE><TARGET>...</TARGET></Paragraph>` のタグで囲まれた形式になっています．
- データのライセンス：[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.ja).

## 注意事項

- 自動翻訳テキストは自動翻訳システムにより生成されたものであり，文章の内容が原文に忠実でなかったり，翻訳誤りを含む場合がありますので，ご注意ください．
- 自動翻訳テキストの正確さについての評価は，今後実施し，その結果を公開する予定です．

## 更新履歴

- 2026/02/09 data-20260207 公開

## 本データの管理者

Shohei Higashiyama (NICT)
