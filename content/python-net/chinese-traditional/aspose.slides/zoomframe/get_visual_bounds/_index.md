---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
取得根據其已渲染內容計算出的形狀之視覺邊界。

### Returns
一個 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef) 代表形狀的視覺邊界
             在投影片座標系統中。

```python
def get_visual_bounds(self):
    ...
```

### 備註
返回的矩形表示所有內容的軸對齊邊界
             由形狀在投影片座標空間渲染期間產生的。

這些邊界可能與形狀的模型邊界不同
             ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
             且可能包含負座標，如果已渲染的內容延伸
             超出投影片原點。

視覺邊界會考慮渲染相關的因素，例如
             轉換（例如旋轉）、線寬與接合、
             文字版面配置與溢位、SmartArt 幾何形狀，以及其他版面效應
             影響形狀最終渲染外觀的因素。

返回的邊界不會被裁剪至投影片矩形內。

### 另請參閱
* 類別 [`ZoomFrame`](/slides/python-net/zh-hant/aspose.slides/zoomframe)
* 類別 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)