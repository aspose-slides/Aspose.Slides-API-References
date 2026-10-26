---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
取得根據已渲染內容計算的圖形之視覺邊界。

### 回傳

一個 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef) 代表圖形之視覺邊界
             在投影片座標系統中。



```python
def get_visual_bounds(self):
    ...
```


### 備註

返回的矩形代表所有內容
             由圖形在投影片座標空間中渲染時產生的軸對齊邊界。

這些邊界可能與圖形的模型邊界不同
             ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
             且如果已渲染的內容延伸超過投影片原點，可能包含負坐標。

視覺邊界會考慮渲染相關的方面，例如
             變換（例如旋轉）、筆劃寬度與接合、
             文字排版與溢位、SmartArt 幾何形狀，以及其他版面效果，
             這些會影響圖形的最終渲染外觀。

返回的邊界不會被裁剪至投影片矩形。



### 另請參閱
* 類別 [`GroupShape`](/slides/python-net/zh-hant/aspose.slides/groupshape)
* 類別 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)