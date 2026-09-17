---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
シェイプのレンダリングされたコンテンツから計算されたビジュアル境界を取得します。

### Returns
**aspose.slides.RectangleF** はスライド座標系でシェイプのビジュアル境界を表します。

```python
def get_visual_bounds(self):
    ...
```

### Remarks
返される矩形は、スライド座標空間でレンダリング中にシェイプによって生成されたすべてのコンテンツの軸平行境界を表します。

これらの境界はシェイプのモデル境界 ([`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height)) と異なる場合があり、レンダリングされたコンテンツがスライドの原点を超えると負の座標を含むことがあります。

ビジュアル境界は、変換（例: 回転）、ストローク幅とジョイン、テキストレイアウトとオーバーフロー、SmartArt のジオメトリ、その他最終的なレンダリング外観に影響を与えるレイアウト効果など、レンダリングに関連する側面を考慮します。

返される境界はスライド矩形にクリップされません。

### See Also
* class [`AutoShape`](/slides/python-net/ja/aspose.slides/autoshape)
* module [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)