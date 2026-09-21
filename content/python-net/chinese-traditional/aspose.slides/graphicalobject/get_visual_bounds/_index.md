---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/graphicalobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
取得根據已渲染內容計算出的圖形之視覺邊界。

### Returns

A **aspose.slides.RectangleF**，代表圖形在投影片座標系中的視覺邊界
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

回傳的矩形表示在投影片座標空間中，圖形在呈現過程中產生的所有內容之軸對齊邊界。
            
這些邊界可能與圖形的模型邊界 ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
不同，且如果已渲染的內容超出投影片原點，可能包含負坐標。
            
視覺邊界會考慮與呈現相關的因素，例如變換（例如旋轉）、筆畫寬度與接點、文字布局與溢位、SmartArt 幾何形狀，以及其他影響圖形最終呈現外觀的布局效果。
            
回傳的邊界不會被裁剪至投影片矩形。



### See Also
* 類別 [`GraphicalObject`](/slides/python-net/zh-hant/aspose.slides/graphicalobject)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)