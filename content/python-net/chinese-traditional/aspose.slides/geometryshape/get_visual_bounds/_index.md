---
title: get_visual_bounds method
second_title: Aspose.Slides 用於 Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/geometryshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
取得根據其已渲染內容計算出的形狀視覺邊界。

### 回傳

A **aspose.slides.RectangleF**，表示形狀在投影片座標中的視覺邊界
             .

```python
def get_visual_bounds(self):
    ...
```

### 備註

返回的矩形表示在投影片座標空間中，形狀在呈現過程中產生的所有內容之軸對齊邊界
             。

這些邊界可能與形狀的模型邊界
             ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
             不同，且如果已渲染內容延伸超過投影片原點，可能會包含負座標
             。

視覺邊界考慮了與渲染相關的各種因素，例如變換（例如旋轉）、筆畫寬度與接合、文字版面配置與溢位、SmartArt 幾何形狀，以及其他會影響形狀最終呈現外觀的版面效果
             。

返回的邊界不會被裁切至投影片矩形
             。

### 另請參閱
* 類別 [`GeometryShape`](/slides/python-net/zh-hant/aspose.slides/geometryshape)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)