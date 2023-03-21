# GeoJSON AFFINE

## やりたいこと
法務省XML地図をGeoJSONに変換したものを、D&Dで読み込んで（ファイル選択でもOK）,フリーハンドで移動して場所合わせをして保存したい

## 考えている手順

1. GeoJSONファイルを読み込む。GeoJSONの中心を計算し、地図の中心との差分を取って、地図の中心に平行移動する
2. 中心に持ってきたフィアルを [Leaflet.Path.Transform](https://github.com/w8r/Leaflet.Path.Transform)で、位置合わせする
3. 変化した結果を、DLもしくはgistにアップロードする

## 現状

1.のところで、挫折ｗ  
というか、D&Dで読み込みができるが、並行移動すらできないｗ

