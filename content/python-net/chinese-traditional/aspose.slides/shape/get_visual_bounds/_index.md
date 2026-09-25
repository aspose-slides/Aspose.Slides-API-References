---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/shape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
取得依據已渲染內容計算出的形狀的可視邊界。

### 回傳值

一個 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)，表示形狀的可視邊界
             位於投影片座標系統中。

```python
def get_visual_bounds(self):
    ...
```

### 備註

返回的矩形表示形狀於渲染過程中產生的所有內容在投影片座標空間中的軸對齊邊界。
            
這些邊界可能與形狀的模型邊界 ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
             不同，且若已渲染的內容超出投影片原點，可能包含負座標。
            
可視邊界考慮了渲染相關的因素，例如變換（例如旋轉）、筆畫寬度與接合、文字版面配置與溢位、SmartArt 幾何形狀以及其他影響形狀最終渲染外觀的版面效果。
            
返回的邊界不會被裁剪至投影片矩形。

### 另請參閱
* 類別 [`Shape`](/slides/python-net/zh-hant/aspose.slides/shape)
* 類別 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)