---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/graphicalobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
取得根據已渲染內容計算出的形狀視覺邊界。

### 回傳值
一個 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef) 表示形狀在投影片座標中的視覺邊界。

```python
def get_visual_bounds(self):
    ...
```

### 備註
返回的矩形表示在投影片座標空間中形狀渲染期間產生的所有內容的軸對齊邊界。

這些邊界可能與形狀的模型邊界 ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height)) 不同，且如果已渲染內容超出投影片原點，可能包含負座標。

視覺邊界會考慮與渲染相關的各種因素，例如變換（例如旋轉）、筆劃寬度與接合、文字版面與溢位、SmartArt 幾何形狀以及其他影響形狀最終渲染外觀的版面效果。

返回的邊界不會被裁切至投影片矩形。

### 參見
* 類別 [`GraphicalObject`](/slides/python-net/zh-hant/aspose.slides/graphicalobject)
* 類別 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)