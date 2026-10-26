---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
取得形狀的視覺邊界，該邊界是根據其已渲染內容計算的。

### 返回值

一個 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)，表示形狀在投影片座標系統中的視覺邊界



```python
def get_visual_bounds(self):
    ...
```


### 備註
The returned rectangle represents the axis-aligned bounds of all content
             由形狀在投影片坐標空間渲染時產生的內容。

These bounds may differ from the shape's model bounds
             ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
             且如果已渲染的內容延伸
             超出投影片原點。

The visual bounds take into account rendering-related aspects such as
             變換（例如旋轉）、筆畫寬度與接合處，
             文字版面配置與溢位、SmartArt 幾何形狀，以及其他版面效果
             這些會影響形狀最終的渲染外觀。

The returned bounds are not clipped to the slide rectangle.
返回的邊界不會被裁剪至投影片矩形。

### 參見
* 類別 [`Connector`](/slides/python-net/zh-hant/aspose.slides/connector)
* 類別 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)