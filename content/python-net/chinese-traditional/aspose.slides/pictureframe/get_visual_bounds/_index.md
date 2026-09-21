---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
取得形狀依其已渲染內容計算出的視覺邊界。

### 回傳

一個 **aspose.slides.RectangleF**，代表形狀在投影片座標中的視覺邊界。

```python
def get_visual_bounds(self):
    ...
```

### 備註

The returned rectangle represents the axis-aligned bounds of all content
             代表所有內容在投影片座標空間中由形狀渲染產生的軸向對齊邊界。

These bounds may differ from the shape's model bounds
             ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
             這些邊界可能與形狀的模型邊界不同，且若渲染內容超出投影片原點，可能包含負座標。

The visual bounds take into account rendering-related aspects such as
             變換（例如旋轉）、筆畫寬度與接合、文字版面配置與溢位、SmartArt 幾何以及其他影響形狀最終渲染外觀的版面效果。

The returned bounds are not clipped to the slide rectangle.
             返回的邊界不會被裁剪到投影片矩形。

### 另請參閱
* 類別 [`PictureFrame`](/slides/python-net/zh-hant/aspose.slides/pictureframe)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)