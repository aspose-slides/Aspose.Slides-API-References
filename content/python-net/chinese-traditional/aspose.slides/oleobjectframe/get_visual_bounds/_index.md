---
title: get_visual_bounds method
second_title: Aspose.Slides for Python 透過 .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
取得形狀的視覺邊界，此邊界是根據其已渲染的內容計算的。

### 回傳值

一個 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)，代表形狀在投影片座標系中的視覺邊界。

```python
def get_visual_bounds(self):
    ...
```

### 備註

回傳的矩形表示所有由形狀在投影片座標空間中渲染時產生的內容之軸對齊邊界。

這些邊界可能與形狀的模型邊界 ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height)) 不同，且如果已渲染的內容超出投影片原點，可能包含負座標。

視覺邊界會考慮渲染相關的因素，例如變換（例如旋轉）、筆畫寬度與接合、文字版面配置與溢位、SmartArt 幾何形狀，以及其他會影響形狀最終渲染外觀的版面效果。

回傳的邊界不會被裁切至投影片矩形。

### 另請參閱
* 類別 [`OleObjectFrame`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe)
* 類別 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)