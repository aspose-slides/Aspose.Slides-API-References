---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
取得形狀的視覺邊界，該邊界根據其渲染內容計算。

### 回傳
一個 **aspose.slides.RectangleF**，代表形狀在投影片座標中的視覺邊界。

```python
def get_visual_bounds(self):
    ...
```

### 備註
返回的矩形代表在投影片座標空間中形狀渲染時產生的所有內容的軸對齊邊界。

這些邊界可能與形狀的模型邊界 ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height)) 不同，且如果渲染的內容超出投影片原點，可能包含負座標。

視覺邊界考慮了渲染相關的因素，例如變換（例如旋轉）、筆畫寬度與接合、文字布局與溢位、SmartArt 幾何形狀以及其他影響形狀最終渲染外觀的版面效果。

返回的邊界不會被裁剪到投影片矩形內。

### 參見
* 類別 [`AudioFrame`](/slides/python-net/zh-hant/aspose.slides/audioframe)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)