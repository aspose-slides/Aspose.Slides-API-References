---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
取得形狀的視覺邊界，該邊界是根據其已渲染內容計算得出。

### 傳回

一個 **aspose.slides.RectangleF**，代表形狀在投影片座標中的視覺邊界
             。

```python
def get_visual_bounds(self):
    ...
```

### 備註

回傳的矩形代表所有內容的軸對齊邊界
             由形狀在投影片座標空間渲染時產生的內容。

             這些邊界可能與形狀的模型邊界不同
             ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
             且如果已渲染內容超出投影片原點，可能包含負座標。

             視覺邊界會考慮渲染相關的因素，例如
             變換（例如旋轉）、筆畫寬度與接合方式、
             文字版面配置與溢位、SmartArt 幾何形狀，以及其他影響形狀最終渲染外觀的版面效果。

             回傳的邊界不會被裁剪至投影片矩形。

### 另請參閱
* 類別 [`Chart`](/slides/python-net/zh-hant/aspose.slides.charts/chart)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 程式庫 [`Aspose.Slides`](/slides/python-net)