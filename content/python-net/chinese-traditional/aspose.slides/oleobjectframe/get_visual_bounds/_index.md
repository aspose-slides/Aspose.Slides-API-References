---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
取得根據已呈現內容計算出的圖形的視覺邊界。

### 返回值

一個 **aspose.slides.RectangleF**，代表圖形在投影片坐標系中的視覺邊界。

```python
def get_visual_bounds(self):
    ...
```

### 備註

返回的矩形代表在投影片坐標空間中，圖形在渲染期間產生的所有內容的軸對齊邊界。
             
這些邊界可能與圖形的模型邊界 ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
不同；如果已呈現的內容超出投影片原點，則可能包含負座標。
             
視覺邊界會考慮渲染相關的因素，例如變換（例如旋轉）、筆畫寬度與接合、文字版面配置與溢位、SmartArt 幾何形狀，以及其他會影響圖形最終呈現外觀的版面效果。
             
返回的邊界不會被裁切至投影片矩形。

### 另請參閱
* 類別 [`OleObjectFrame`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)