# mypkg
# 課題提出内容ros2のリポジトリ

![test](https://github.com/yukihiroshiojima/mypkg/actions/workflows/test.yml/badge.svg)


# プログラム内容

talkerというノードから数字をカウントしてcountupというトピックを通じて送信し、listenerというノードが読み取り、出力する


# 実行例と実行結果

```
端末１: $ ros2 run mypkg talker

端末２: $ ros2 run mypkg listener

[INFO] [1672457273.794839704] [listener]: Listen: 0
[INFO] [1672457274.260601384] [listener]: Listen: 1
[INFO] [1672457274.762110243] [listener]: Listen: 2
[INFO] [1672457275.262290261] [listener]: Listen: 3
[INFO] [1672457275.762691683] [listener]: Listen: 4
[INFO] [1672457276.262535997] [listener]: Listen: 5
[INFO] [1672457276.762765466] [listener]: Listen: 6
[INFO] [1672457277.262665703] [listener]: Listen: 7
[INFO] [1672457277.762693175] [listener]: Listen: 8
[INFO] [1672457278.263079582] [listener]: Listen: 9
[INFO] [1672457278.763043923] [listener]: Listen: 10
```


# 動作確認済み環境

* Ubuntu20.04


# ライセンス

* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです
* [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022
* © 2022 Yukihiro Shiojima
