---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
取得根據已呈現內容計算出的圖形視覺邊界。

### 返回

一個 **aspose.slides.RectangleF**，表示圖形的視覺邊界
             在投影片座標系統中。



```python
def get_visual_bounds(self):
    ...
```


### 備註

返回的矩形表示所有內容的軸對齊邊界
             這些內容由圖形在投影片座標空間的渲染過程中產生。
             
這些邊界可能與圖形的模型邊界不同
             ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
             且如果已渲染的內容超出投影片原點，可能包含負座標
             超出投影片原點。

視覺邊界會考慮與渲染相關的各種因素，例如
             轉換（例如旋轉）、筆劃寬度與接合，
             文字版面配置與溢位、SmartArt 幾何形狀，以及其他版面效果
             這些會影響圖形最終渲染外觀。

返回的邊界不會被裁剪至投影片矩形。



### 另見
* 類別 [`SummaryZoomFrame`](/slides/python-net/zh-hant/aspose.slides/summaryzoomframe)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)