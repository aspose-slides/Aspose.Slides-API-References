---
title: get_visual_bounds method
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
取得形狀根據其渲染內容計算的視覺邊界。

### 回傳
一個 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)，表示形狀的視覺邊界
             在投影片座標中。

```python
def get_visual_bounds(self):
    ...
```

### 備註
返回的矩形表示在投影片座標空間中，形狀的所有內容的軸對齊邊界
             由形狀在渲染期間產生。

這些邊界可能與形狀的模型邊界
             ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
             不同，且如果渲染的內容超出投影片原點，可能包含負座標
             。

視覺邊界會考慮渲染相關的因素，例如
             變換（例如旋轉）、筆畫寬度與接合、文字版面配置與溢位、SmartArt 幾何形狀，以及其他影響形狀最終渲染外觀的版面效果
             。

返回的邊界
             不會被裁剪至投影片矩形
             。

### 另請參閱
* 類別 [`VideoFrame`](/slides/python-net/zh-hant/aspose.slides/videoframe)
* 類別 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)