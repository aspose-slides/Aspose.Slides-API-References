---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
描画されたコンテンツから計算されたシェイプの視覚的境界を取得します。

### Returns

シェイプの視覚的境界をスライド座標系で表す[`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef)です。

```python
def get_visual_bounds(self):
    ...
```

### Remarks

返された矩形は、スライド座標空間でレンダリング中にシェイプによって生成されたすべてのコンテンツの軸に平行な境界を表します。

これらの境界はシェイプのモデル境界（[`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height)）と異なる場合があり、描画されたコンテンツがスライドの原点を超える場合には負の座標を含むことがあります。

視覚的境界は、変換（例: 回転）やストローク幅とジョイン、テキストレイアウトとオーバーフロー、SmartArt のジオメトリ、その他シェイプの最終的な描画外観に影響を与えるレイアウト効果など、レンダリングに関する要素を考慮します。

返された境界はスライド矩形にクリップされません。

### See Also
* クラス [`GroupShape`](/slides/python-net/ja/aspose.slides/groupshape)
* クラス [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)