---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Gets the visual bounds of the shape calculated from its rendered content.

### 回傳值

一個 **aspose.slides.RectangleF**，表示形狀的視覺邊界
             在投影片座標系統中。



```python
def get_visual_bounds(self):
    ...
```


### 備註

返回的矩形代表所有內容的軸對齊邊界
             由形狀在投影片座標空間中渲染時產生。

這些邊界可能與形狀的模型邊界不同
             ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
             且如果已渲染的內容擴展
             超出投影片原點。

視覺邊界會考慮與渲染相關的方面，例如
             變換（例如，旋轉）、筆畫寬度與接合、
             文字版面配置與溢位、SmartArt 幾何形狀，以及其他版面效果
             影響形狀最終呈現外觀的因素。

返回的邊界未被裁剪至投影片矩形。



### 參見
* 類別 [`GroupShape`](/slides/python-net/zh-hant/aspose.slides/groupshape)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)