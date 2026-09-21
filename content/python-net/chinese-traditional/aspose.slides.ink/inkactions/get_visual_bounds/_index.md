---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
取得形狀的視覺範圍，根據其已渲染內容計算。

### 返回

一個 **aspose.slides.RectangleF**，代表形狀在投影片座標系統中的視覺範圍



```python
def get_visual_bounds(self):
    ...
```


### 備註

返回的矩形表示所有內容在投影片座標空間中渲染時的軸對齊範圍。

這些範圍可能與形狀的模型範圍 ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height)) 不同，且如果已渲染內容超出投影片原點，範圍可能包含負座標。

視覺範圍會考慮與渲染相關的因素，例如變換（例如旋轉）、筆畫寬度與接合、文字布局與溢位、SmartArt 幾何形狀以及其他影響形狀最終渲染外觀的版面效果。

返回的範圍不會被裁剪至投影片矩形。

### 另見
* 類別 [`InkActions`](/slides/python-net/zh-hant/aspose.slides.ink/inkactions)
* 模組 [`aspose.slides.ink`](/slides/python-net/zh-hant/aspose.slides.ink)
* 函式庫 [`Aspose.Slides`](/slides/python-net)