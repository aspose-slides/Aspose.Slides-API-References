---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
取得形狀根據其已呈現內容計算出的視覺邊界。

### 返回

一個 **aspose.slides.RectangleF**，代表形狀在投影片座標中的視覺邊界。

```python
def get_visual_bounds(self):
    ...
```

### 備註

返回的矩形代表在投影片座標空間中形狀渲染時產生的所有內容的軸對齊邊界。

這些邊界可能與形狀的模型邊界 ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
不同，且如果已呈現的內容超出投影片原點，可能包含負座標。

視覺邊界會考慮渲染相關的因素，例如變換（例如旋轉）、筆畫寬度與接合、文字佈局與溢位、SmartArt 幾何形狀，以及其他影響形狀最終呈現外觀的佈局效果。

返回的邊界不會被裁剪到投影片矩形內。

### 另請參閱
* 類別 [`ZoomObject`](/slides/python-net/zh-hant/aspose.slides/zoomobject)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)