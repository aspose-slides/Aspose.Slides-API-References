---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
取得根據其已渲染內容計算出的形狀視覺邊界。

### 回傳

一個 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)，代表形狀在投影片座標中的視覺邊界



```python
def get_visual_bounds(self):
    ...
```


### 備註

回傳的矩形代表在投影片座標空間中由形狀在渲染期間產生的所有內容的軸對齊邊界。

這些邊界可能與形狀的模型邊界 ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height)) 不同，且如果已渲染的內容超出投影片原點，可能會包含負座標。

視覺邊界會考慮渲染相關的因素，例如變換（例如旋轉）、筆畫寬度與接合、文字版面配置與溢位、SmartArt 幾何形狀，以及其他影響形狀最終渲染外觀的版面效果。

回傳的邊界不會被裁剪至投影片矩形。



### 另見
* 類別 [`SmartArtShape`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape)
* 類別 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)
* 模組 [`aspose.slides.smartart`](/slides/python-net/zh-hant/aspose.slides.smartart)
* 函式庫 [`Aspose.Slides`](/slides/python-net)