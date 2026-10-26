---
title: get_visual_bounds method
second_title: Aspose.Slides 適用於 Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
取得從已呈現內容計算出的圖形視覺邊界。

### 返回值

一個 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)，代表圖形在投影片座標中的視覺邊界
             in slide coordinates.



```python
def get_visual_bounds(self):
    ...
```


### 備註

返回的矩形代表在投影片座標空間中由圖形在呈現過程中產生的所有內容的軸對齊邊界
             
             這些邊界可能與圖形的模型邊界 ([`Shape.x`](/slides/python-net/zh-hant/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/zh-hant/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/zh-hant/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/zh-hant/aspose.slides/shape/height))
             不同，且如果已呈現內容超出投影片原點，邊界可能包含負座標
             
             視覺邊界會考慮與呈現相關的因素，例如變換（例如 rotation），筆劃寬度與接合，文字版面配置與 overflow，SmartArt 幾何形狀，以及其他影響圖形最終呈現外觀的版面效果
             
             返回的邊界不會被裁剪到投影片矩形內



### 另見
* 類別 [`PictureFrame`](/slides/python-net/zh-hant/aspose.slides/pictureframe)
* 類別 [`RectangleF`](/slides/python-net/zh-hant/aspose.slides/rectanglef)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)