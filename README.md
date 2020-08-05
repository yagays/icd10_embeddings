# ICD10 Embeddings

## 概要
ウェブから収集した医療分野における大規模テキストデータから単語の分散表現学習し、疾患の意味的な類似度を求めた疾患ベクトルです。

詳細は下記ブログ記事を参照ください。

[医療分野の大規模テキストデータで学習した分散表現から、疾患の類似度を求める \- Out\-of\-the\-box](https://yag-ays.github.io/project/icd10-embeddings/)

## 内容

- `icd10_embeddings.txt`: ICDコードに対応する疾患の埋め込みベクトル
- `icd_name.json`: ICDコードにに対応する疾患名を最大3つ付与した対応表
- `sample.ipynb`: サンプルコード

## クレジット
この疾患ベクトルは「万病辞書」`MANBYO_201907`を利用して構築しました。

[MEDNLP 医療言語処理グループ 万病辞書](http://sociocom.jp/~data/2018-manbyo/index.html)
