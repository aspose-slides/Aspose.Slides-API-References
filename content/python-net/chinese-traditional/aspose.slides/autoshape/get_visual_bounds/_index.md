---
title: get_visual_bounds method
second_title: Aspose.Slides 用於 .NET 的 Python API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
取得形狀的視覺邊界，該邊界根據其已呈現的內容計算。

### 返回

A **aspose.slides.RectangleF**，表示形狀在投影片座標中的視覺邊界
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### 備註

返回的矩形表示形狀在投影片座標空間中渲染時產生的所有內容的軸對齊邊界。
            
             這些邊界可能與形狀的模型邊界 ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height)) 不同，且如果已呈現的內容超出投影片原點，可能包含負座標。
            
             視覺邊界會考慮渲染相關的因素，例如變形（例如旋轉）、筆畫寬度與接合、文字版面配置與溢位、SmartArt 幾何形狀，以及其他會影響形狀最終呈現外觀的版面效果。
            
             返回的邊界不會被裁剪到投影片矩形內。



### 另請參閱
* 類別 [`AutoShape`](/slides/python-net/zh-hant/aspose.slides/autoshape)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)