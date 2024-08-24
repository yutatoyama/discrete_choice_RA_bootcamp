# トピックレクチャー：離散選択モデル

担当：遠山祐太

最終更新：2024年8月24日

## ファイルの説明

以下それぞれについて、HTMLファイル、PDFファイル、RMDファイル（ソース・ファイル）があります。

- `slide_1_lecture.XXX`: 講義スライド
- `slide_2_practice.XXX`: 演習問題
- `slide_3_appendix.XXX`: 補足資料１：理論編
- `slide_4_code_scratch.XXX`: 補足資料２：パッケージを利用しない多項ロジットモデルの推定

講義においては、slide_1_lecture と slide_2_practice を中心にカバーします。

## 必要なパッケージ

以下のパッケージについてのインストールをお願いします。

```
library("tidyverse")
library("knitr")
library("mlogit") # ロジットモデル推定のためのパッケージ
library("stargazer") # 推定結果の表作成
library("optimx") # 数値最適化のためのパッケージ
```

