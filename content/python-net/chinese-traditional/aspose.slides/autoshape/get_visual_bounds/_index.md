---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
取得形狀的視覺邊界，該邊界根據其已渲染的內容計算。

### 傳回值

一個 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)，表示形狀在投影片座標中的視覺邊界
             在投影片座標系中。



```python
def get_visual_bounds(self):
    ...
```


### 備註

返回的矩形表示形狀在投影片座標空間中渲染時產生的所有內容的軸對齊界限。
             
這些界限可能與形狀的模型界限不同
             ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
             且如果已渲染的內容延伸超過投影片原點，則可能包含負坐標。
             
視覺邊界會考慮渲染相關的因素，例如
             變換（例如旋轉）、筆劃寬度與連接、
             文字版面配置與溢位、SmartArt 幾何形狀，以及其他版面效果
             這些會影響形狀最終的渲染外觀。
             
返回的界限不會被裁剪至投影片矩形。



### 另請參閱
* 類別 [`AutoShape`](/slides/python-net/zh-hant/aspose.slides/autoshape)
* 類別 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)