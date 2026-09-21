---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
取得根據其渲染內容計算出的形狀視覺邊界。

### Returns

一個 **aspose.slides.RectangleF**，代表
             以投影片座標表示的形狀視覺邊界。



```python
def get_visual_bounds(self):
    ...
```


### Remarks

返回的矩形表示在投影片座標空間中形狀渲染時產生的所有內容的軸對齊邊界。
            
             這些邊界可能與形狀的模型邊界 ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height)) 不同，且如果渲染內容延伸超過投影片原點，可能包含負座標。
            
             視覺邊界會考慮渲染相關的因素，例如變換（例如旋轉）、筆劃寬度與接合、文字版面與溢出、SmartArt 幾何以及其他影響形狀最終渲染外觀的版面效果。
            
             返回的邊界不會被裁剪至投影片矩形。



### See Also
* class [`Table`](/slides/python-net/zh-hant/aspose.slides/table)
* module [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)