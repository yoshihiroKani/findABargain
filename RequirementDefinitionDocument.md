# RequirementDefinitionDocument

## target EC site list
* Amazon
* e-bay
* 楽天
* 駿河屋
* Yahoo! ショッピング
* 保留
  * メルカリ
  * ジモティー
  * Yahoo! オークション
  
## system flow
1. Amazonの商品を重複なくピックアップする
    * ASINを1~ループする　など
1. Google Chromeのグローバルサーチ機能に1.の商品情報を渡す
1. 2.の結果を抽出する
1. 3.の結果に対して、Amazonとその他のショップの価格差を計算する
1. 4.の結果の絶対値が大きい物に対して、以下を出力する
    * Amazonの価格
    * 比較対象のショップ名
    * 比較対象のショップの商品価格
