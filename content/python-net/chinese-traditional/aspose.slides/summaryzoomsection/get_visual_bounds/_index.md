---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
取得根據已渲染內容計算的形狀視覺邊界。

### 返回

一個 **aspose.slides.RectangleF**，表示以投影片座標表示的形狀視覺邊界。



```python
def get_visual_bounds(self):
    ...
```


### 備註

返回的矩形表示所有內容的軸對齊邊界
             由形狀在投影片座標空間的渲染過程中產生。

             
這些邊界可能與形狀的模型邊界不同
             ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
             並且如果已渲染的內容超出投影片原點，可能包含負座標。

             
視覺邊界考慮了渲染相關的因素，例如
             變換（例如旋轉）、筆畫寬度與接合、
             文字版面配置與溢位、SmartArt 幾何形狀以及其他影響形狀最終渲染外觀的版面效果。

             
返回的邊界未被裁剪至投影片矩形。


### 另請參閱
* 類別 [`SummaryZoomSection`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)