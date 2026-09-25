---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
取得根據其已呈現內容計算出的形狀視覺邊界。

### 返回
一個 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)，表示以投影片座標表示的形狀視覺邊界。

```python
def get_visual_bounds(self):
    ...
```

### 備註
返回的矩形代表在投影片座標空間中，形狀在呈現過程中產生的所有內容的軸對齊邊界。

這些邊界可能與形狀的模型邊界 ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height)) 不同，且若已呈現的內容延伸超過投影片原點，可能會包含負座標。

視覺邊界會考慮渲染相關的因素，例如變換（例如旋轉）、筆畫寬度與接合、文字版面配置與溢位、SmartArt 幾何形狀，以及其他影響形狀最終呈現外觀的版面效果。

返回的邊界不會被裁剪至投影片矩形。

### 另請參閱
* 類別 [`LegacyDiagram`](/slides/python-net/zh-hant/aspose.slides/legacydiagram)
* 類別 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)