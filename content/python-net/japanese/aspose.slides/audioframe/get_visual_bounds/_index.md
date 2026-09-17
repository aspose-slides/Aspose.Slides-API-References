---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
シェイプのレンダリングされたコンテンツから計算されたビジュアル境界を取得します。

### Returns

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             in slide coordinates.

```python
def get_visual_bounds(self):
    ...
```

### Remarks

The returned rectangle represents the axis-aligned bounds of all content
             produced by the shape during rendering in slide coordinate space.

These bounds may differ from the shape's model bounds
             ([`Shape.x`](/slides/python-net/ja/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/ja/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/ja/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/ja/aspose.slides/shape/height))
             and may contain negative coordinates if the rendered content extends
             beyond the slide origin.

The visual bounds take into account rendering-related aspects such as
             transformations (for example, rotation), stroke width and joins,
             text layout and overflow, SmartArt geometry, and other layout effects
             that influence the final rendered appearance of the shape.

The returned bounds are not clipped to the slide rectangle.

### See Also
* クラス [`AudioFrame`](/slides/python-net/ja/aspose.slides/audioframe)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)