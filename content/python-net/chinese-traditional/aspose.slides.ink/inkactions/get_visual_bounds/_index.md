---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
取得形狀從其已呈現內容計算出的視覺邊界。

### 返回值

一個 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)，表示形狀在投影片座標系統中的視覺邊界。
```python
def get_visual_bounds(self):
    ...
```

### 備註

返回的矩形表示所有內容的軸對齊邊界
             由形狀在投影片座標空間中渲染時產生的內容。

             這些邊界可能與形狀的模型邊界不同
             ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
             且如果已渲染的內容延伸
             超出投影片原點，則可能包含負座標。

             視覺邊界會考慮渲染相關的因素，例如
             變換（例如，旋轉）、筆畫寬度與接合，
             文字排版與溢位、SmartArt 幾何形狀，以及其他版面效果
             這些因素會影響形狀最終的渲染外觀。

             返回的邊界不會被裁剪至投影片矩形。

### 另請參閱
* 類別 [`InkActions`](/slides/python-net/zh-hant/aspose.slides.ink/inkactions)
* 類別 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)
* 模組 [`aspose.slides.ink`](/slides/python-net/zh-hant/aspose.slides.ink)
* 程式庫 [`Aspose.Slides`](/slides/python-net)