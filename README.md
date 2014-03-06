# botyo_koufu

裁判所の [傍聴券交付情報][botyo_koufu] から定期的にデータを取得し
整理して保存しています。

[botyo_koufu]: http://www.courts.go.jp/kengaku/botyo_koufu/index.html

## データ形式

- `/data/court-no.csv`  
  `裁判所番号,裁判所名`

- `/data/裁判所番号/年-月-日.csv`  
  `裁判所名,日時・場所,事件名,備考`
