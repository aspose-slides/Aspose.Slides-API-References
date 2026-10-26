---
title: get_visual_bounds method
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
取得依據形狀已渲染內容計算出的視覺範圍。

### 回傳值

A [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef) that represents the visual bounds of the shape
             在投影片座標系中。

```python
def get_visual_bounds(self):
    ...
```

### 備註
The returned rectangle represents the axis-aligned bounds of all content
             產生於形狀在投影片坐標空間中渲染時的所有內容的軸對齊邊界。
            
             These bounds may differ from the shape's model bounds
             ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
             且若已渲染的內容超出投影片原點，可能包含負座標。
            
             The visual bounds take into account rendering-related aspects such as
             變換（例如旋轉）、筆劃寬度與接合、文字版面配置與溢位、SmartArt 幾何形狀，以及其他會影響形狀最終渲染外觀的版面效果。
            
             The returned bounds are not clipped to the slide rectangle。

### 另見
* 類別 [`SummaryZoomFrame`](/slides/python-net/zh-hant/aspose.slides/summaryzoomframe)
* 類別 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)