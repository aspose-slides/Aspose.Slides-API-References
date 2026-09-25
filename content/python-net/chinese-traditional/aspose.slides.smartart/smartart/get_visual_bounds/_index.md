---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
取得根據其渲染內容計算出的形狀視覺邊界。

### 回傳

一個 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)，表示形狀在投影片座標系中的視覺邊界
             in slide coordinates.

```python
def get_visual_bounds(self):
    ...
```

### 備註

The returned rectangle represents the axis-aligned bounds of all content
             produced by the shape during rendering in slide coordinate space.
            
             These bounds may differ from the shape's model bounds
             ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
             and may contain negative coordinates if the rendered content extends
             beyond the slide origin.
            
             The visual bounds take into account rendering-related aspects such as
             transformations (for example, rotation), stroke width and joins,
             text layout and overflow, SmartArt geometry, and other layout effects
             that influence the final rendered appearance of the shape.
            
             The returned bounds are not clipped to the slide rectangle.

### 另請參閱
* 類別 [`SmartArt`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart)
* 類別 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)
* 模組 [`aspose.slides.smartart`](/slides/python-net/zh-hant/aspose.slides.smartart)
* 函式庫 [`Aspose.Slides`](/slides/python-net)