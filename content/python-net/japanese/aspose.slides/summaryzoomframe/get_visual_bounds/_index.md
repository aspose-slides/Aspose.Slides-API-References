---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
レンダリングされたコンテンツから計算された、シェイプの視覚的境界を取得します。

### 戻り値

[`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef) は、スライド座標系でシェイプの視覚的境界を表すものです。



```python
def get_visual_bounds(self):
    ...
```


### 備考

返される矩形は、スライド座標空間でレンダリング中にシェイプによって生成されたすべてのコンテンツの軸に平行な境界を表します。

これらの境界は、シェイプのモデル境界 ([`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height)) と異なる場合があり、レンダリングされたコンテンツがスライドの原点を超えている場合、負の座標を含むことがあります。

視覚的境界は、変換（例: 回転）、ストローク幅とジョイン、テキストレイアウトとオーバーフロー、SmartArt のジオメトリ、その他シェイプの最終的な描画外観に影響を与えるレイアウト効果など、レンダリングに関連する要素を考慮します。

返された境界はスライド矩形にクリップされません。



### 参照
* クラス [`SummaryZoomFrame`](/slides/python-net/ja/aspose.slides/summaryzoomframe)
* クラス [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)