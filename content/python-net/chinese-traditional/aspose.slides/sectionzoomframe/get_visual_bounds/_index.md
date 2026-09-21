---
title: get_visual_bounds method
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
取得根據已渲染內容計算出的形狀視覺邊界。

### 返回值

一個 **aspose.slides.RectangleF**，它表示形狀的視覺邊界
             在投影片座標系中。



```python
def get_visual_bounds(self):
    ...
```


### 備註

返回的矩形表示形狀在渲染過程中產生的所有內容
             在投影片座標空間中的軸對齊邊界。
            
             這些邊界可能與形狀的模型邊界不同
             ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
             並且如果已渲染的內容超出投影片原點，可能包含負座標。
            
             視覺邊界會考慮與渲染相關的方面，例如
             變換（例如，旋轉）、筆畫寬度與接合、
             文字版面配置與溢位、SmartArt 幾何形狀，以及其他影響形狀最終渲染外觀的版面效果。
            
             返回的邊界不會被裁剪至投影片矩形。



### 另請參閱
* 類別 [`SectionZoomFrame`](/slides/python-net/zh-hant/aspose.slides/sectionzoomframe)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)