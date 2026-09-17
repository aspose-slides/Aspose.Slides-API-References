---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。

### 戻り値

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             in slide coordinates.

```python
def get_visual_bounds(self):
    ...
```

### 備考
The returned rectangle represents the axis-aligned bounds of all content
             produced by the shape during rendering in slide coordinate space.

             返された矩形は、すべてのコンテンツの軸整列境界を表します
             シェイプがレンダリング中にスライド座標空間で生成したものです。

             These bounds may differ from the shape's model bounds
             ([`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height))
             これらの境界はシェイプのモデル境界と異なる場合があり
             レンダリングされたコンテンツがスライドの原点を超える場合、負の座標を含むことがあります。

             The visual bounds take into account rendering-related aspects such as
             transformations (for example, rotation), stroke width and joins,
             text layout and overflow, SmartArt geometry, and other layout effects
             that influence the final rendered appearance of the shape.
             視覚的境界は、レンダリングに関連する側面を考慮します。例えば、
             変換（例: 回転）、ストローク幅と結合、
             テキストのレイアウトとオーバーフロー、SmartArt のジオメトリ、その他のレイアウト効果、
             それらはシェイプの最終的な描画外観に影響を与えます。

             The returned bounds are not clipped to the slide rectangle.
             返された境界はスライド矩形にクリップされません。

### 参照
* クラス [`InkActions`](/slides/python-net/ja/aspose.slides.ink/inkactions)
* モジュール [`aspose.slides.ink`](/slides/python-net/ja/aspose.slides.ink)
* ライブラリ [`Aspose.Slides`](/slides/python-net)