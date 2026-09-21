---
title: get_visual_bounds method
second_title: Aspose.Slides 適用於 Python 的 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
取得根據已渲染內容計算出的圖形之視覺邊界。

### 回傳

A **aspose.slides.RectangleF**，代表圖形在投影片座標系統中的視覺邊界。

```python
def get_visual_bounds(self):
    ...
```

### 備註
返回的矩形代表所有內容的軸對齊邊界
             由圖形在投影片座標空間中渲染時產生的

             這些邊界可能與圖形的模型邊界不同
             ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
             且如果已渲染的內容超出投影片原點，可能包含負坐標
             超過投影片原點。

             視覺邊界會考慮與渲染相關的因素，例如
             變換（例如旋轉）、筆劃寬度與接合處，
             文字排版與溢出、SmartArt 幾何形狀，以及其他版面配置效果
             會影響圖形最終渲染外觀。

             返回的邊界不會被裁剪至投影片矩形。

### 參見
* 類別 [`Connector`](/slides/python-net/zh-hant/aspose.slides/connector)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)