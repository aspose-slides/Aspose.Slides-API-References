---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/shape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
取得依據其已渲染內容計算出的圖形視覺邊界。

### 回傳
一個 **aspose.slides.RectangleF**，代表圖形在投影片座標系中的視覺邊界

```python
def get_visual_bounds(self):
    ...
```

### 備註
回傳的矩形表示在投影片座標空間中，形狀在渲染過程中產生的所有內容的軸向對齊邊界。  
這些邊界可能與形狀的模型邊界 ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height)) 不同，且如果已渲染的內容超出投影片原點，可能包含負座標。  
視覺邊界會考慮渲染相關的因素，例如變換（如旋轉）、筆畫寬度與接合、文字佈局與溢位、SmartArt 幾何形狀，以及其他影響形狀最終渲染外觀的佈局效果。  
回傳的邊界不會被裁剪至投影片矩形。

### 另見
* 類別 [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)