---
title: get_visual_bounds method
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
取得根據形狀已渲染內容計算出的視覺邊界。

### 回傳值

一個 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)，表示形狀的視覺邊界
             在投影片座標系中。

```python
def get_visual_bounds(self):
    ...
```

### 備註

回傳的矩形代表所有內容的軸對齊邊界
             由形狀在投影片座標空間中渲染時產生的。

這些邊界可能與形狀的模型邊界不同
             ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
             且如果已渲染的內容超出投影片原點，可能包含負座標。

視覺邊界考慮了與渲染相關的各種面向，例如
             變換（例如旋轉）、筆畫寬度與接合處,
             文字版面配置與溢位、SmartArt 幾何形狀，以及其他版面效果,
             這些會影響形狀最終的渲染外觀。

回傳的邊界不會被裁剪至投影片矩形。

### 另請參閱
* 類別 [`SectionZoomFrame`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe)
* 類別 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)