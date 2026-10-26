---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
描画されたコンテンツから計算されたシェイプの視覚的境界を取得します。

### 返り値

[`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef) は、スライド座標系でシェイプの視覚的境界を表します。

```python
def get_visual_bounds(self):
    ...
```

### 備考
返された矩形は、シェイプがレンダリング中に生成したすべてのコンテンツの軸に平行な境界を表します
             スライド座標空間でのレンダリング中にシェイプによって生成された

             
             これらの境界は、シェイプのモデル境界と異なる場合があります
             ([`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height))
             そして、レンダリングされたコンテンツが拡張した場合、負の座標が含まれることがあります
             スライドの原点を超える場合です。

             
             視覚的境界は、次のようなレンダリングに関連する要素を考慮します
             変換（例: 回転）、ストローク幅とジョイン、
             テキストレイアウトとオーバーフロー、SmartArt のジオメトリ、その他のレイアウト効果
             これらはシェイプの最終的なレンダリング外観に影響します

             
             返された境界はスライド矩形にクリップされません

### 参照
* クラス [`Chart`](/slides/python-net/ja/aspose.slides.charts/chart)
* クラス [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)