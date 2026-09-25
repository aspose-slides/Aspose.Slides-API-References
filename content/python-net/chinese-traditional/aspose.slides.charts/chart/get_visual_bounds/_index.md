---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
取得形狀根據其渲染內容計算出的視覺邊界。

### 回傳

一個 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)，表示形狀在投影片座標中的視覺邊界。

```python
def get_visual_bounds(self):
    ...
```

### 備註

返回的矩形代表形狀在渲染過程中於投影片座標空間產生的所有內容之軸對齊邊界。

這些邊界可能與形狀的模型邊界 ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height)) 不同，且如果渲染內容超出投影片原點，則可能包含負座標。

視覺邊界會考慮渲染相關的因素，例如轉換（例如旋轉）、筆劃寬度與接合、文字版面配置與溢位、SmartArt 幾何形狀，以及其他影響形狀最終渲染外觀的版面效果。

返回的邊界不會被裁切至投影片矩形。

### 另請參閱
* 類別 [`Chart`](/slides/python-net/zh-hant/aspose.slides.charts/chart)
* 類別 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)