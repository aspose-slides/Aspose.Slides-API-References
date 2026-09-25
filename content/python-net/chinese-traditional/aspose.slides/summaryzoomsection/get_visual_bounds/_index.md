---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
取得形狀根據其呈現內容計算出的視覺邊界。

### 返回值

一個 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef) 表示形狀在投影片座標中的視覺邊界
              。

```python
def get_visual_bounds(self):
    ...
```

### 備註

返回的矩形表示形狀在呈現過程中於投影片座標空間產生的所有內容之軸對齊邊界。

這些邊界可能與形狀的模型邊界 ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height)) 不同，且若呈現的內容超出投影片原點，可能包含負座標。

視覺邊界會考慮到與呈現相關的因素，例如變換（例如，旋轉）、筆畫寬度與接合、文字版面配置與溢位、SmartArt 幾何，以及其他影響形狀最終呈現外觀的版面效果。

返回的邊界不會被裁剪至投影片矩形。

### 另見
* 類別 [`SummaryZoomSection`](/slides/python-net/zh-hant/aspose.slides/summaryzoomsection)
* 類別 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)