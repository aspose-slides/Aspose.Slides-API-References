---
title: get_visual_bounds method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
取得根據其已渲染內容計算出的圖形視覺邊界。

### 返回

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             在投影片座標系統中。



```python
def get_visual_bounds(self):
    ...
```


### 備註
返回的矩形表示所有內容
             由圖形在投影片座標空間中渲染時產生的內容
            這些邊界可能與圖形的模型邊界不同
            ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
            [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
            且若已渲染的內容延伸，可能包含負坐標
            超過投影片原點
            視覺邊界考慮了與渲染相關的各種因素，例如
            變換（例如旋轉）、筆畫寬度與連接方式，
            文字佈局與溢位、SmartArt 幾何形狀，以及其他佈局效果
            會影響圖形最終渲染外觀
            返回的邊界不會被裁剪到投影片矩形內。



### 另請參閱
* 類別 [`SmartArtShape`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartshape)
* 模組 [`aspose.slides.smartart`](/slides/python-net/zh-hant/aspose.slides.smartart)
* 函式庫 [`Aspose.Slides`](/slides/python-net)