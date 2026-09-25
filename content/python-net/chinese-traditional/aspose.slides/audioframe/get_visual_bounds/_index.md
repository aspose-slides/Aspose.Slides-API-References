---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/audioframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
取得根據其渲染內容計算出的圖形視覺邊界。

### 返回值

一個 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)，代表以投影片座標表示的圖形視覺邊界。

```python
def get_visual_bounds(self):
    ...
```

### 備註

返回的矩形代表在投影片座標空間中，形狀於渲染時產生之所有內容的軸向對齊邊界。  
這些邊界可能與形狀的模型邊界 ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height)) 不同，且若渲染的內容延伸超過投影片原點，這些邊界可能包含負坐標。  
視覺邊界會考慮渲染相關的因素，例如變換（例如旋轉）、筆畫寬度與接合、文字佈局與溢位、SmartArt 幾何形狀，以及其他影響形狀最終渲染外觀的版面效果。  
返回的邊界不會被裁剪至投影片矩形。

### 另請參閱
* 類別 [`AudioFrame`](/slides/python-net/zh-hant/aspose.slides/audioframe)
* 類別 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)