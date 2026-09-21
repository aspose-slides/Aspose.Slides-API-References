---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
取得形狀根據其已呈現內容計算出的可視範圍。

### 返回值

一個 **aspose.slides.RectangleF**，表示形狀在投影片座標中的可視範圍。

```python
def get_visual_bounds(self):
    ...
```

### 備註

返回的矩形表示在投影片座標空間中渲染時形狀產生的所有內容的軸對齊邊界。

這些邊界可能與形狀的模型邊界 ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height)) 不同，且如果已呈現的內容延伸到投影片原點之外，可能包含負座標。

可視範圍會考慮渲染相關的因素，例如變換（例如旋轉）、筆畫寬度與接合、文字版面配置與溢位、SmartArt 幾何形狀，以及其他影響形狀最終呈現外觀的版面效果。

返回的邊界不會被裁剪至投影片矩形。

### 另見
* 類別 [`VideoFrame`](/slides/python-net/zh-hant/aspose.slides/videoframe)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)