---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
レンダリングされたコンテンツから計算された、シェイプの視覚的境界を取得します。

### 戻り値

スライド座標でシェイプの視覚的境界を表す [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef)

```python
def get_visual_bounds(self):
    ...
```

### 備考

返された矩形は、スライド座標空間でレンダリング中にシェイプが生成したすべてのコンテンツの軸平行境界を表します。

これらの境界はシェイプのモデル境界
([`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height))
とは異なる場合があり、レンダリングされたコンテンツがスライドの原点を超えると負の座標を含むことがあります。

視覚的境界は、変換（例: 回転）、ストローク幅とジョイン、テキストレイアウトとオーバーフロー、SmartArt のジオメトリ、その他最終的なレンダリング外観に影響を与えるレイアウト効果など、レンダリングに関連する側面を考慮します。

返された境界はスライド矩形でクリップされません。

### 参照
* クラス [`ZoomFrame`](/slides/python-net/ja/aspose.slides/zoomframe)
* クラス [`RectangleF`](/slides/python-net/ja/aspose.slides/rectanglef)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)