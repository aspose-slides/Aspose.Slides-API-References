---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
取得依據已呈現內容計算出的形狀視覺邊界。

### 返回值

一個 **aspose.slides.RectangleF**，代表形狀在投影片座標系統中的視覺邊界。

```python
def get_visual_bounds(self):
    ...
```

### 備註

回傳的矩形代表在投影片座標空間中，由形狀在呈現過程中產生的所有內容之軸對齊邊界。

這些邊界可能與形狀的模型邊界 ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height)) 不同，且如果已呈現的內容超出投影片原點，可能包含負座標。

視覺邊界會考慮與呈現相關的因素，例如變換（例如旋轉）、筆劃寬度與接合、文字版面配置與溢位、SmartArt 幾何形狀，以及其他影響形狀最終呈現外觀的版面效果。

回傳的邊界不會被裁切至投影片矩形。

### 另請參閱
* 類別 [`SmartArt`](/slides/python-net/zh-hant/aspose.slides.smartart/smartart)
* 模組 [`aspose.slides.smartart`](/slides/python-net/zh-hant/aspose.slides.smartart)
* 函式庫 [`Aspose.Slides`](/slides/python-net)