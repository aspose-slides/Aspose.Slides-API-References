---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/pictureframe/get_image/
weight: 50
---
## get_image(self) {#}
返回形狀縮圖。
            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### 返回

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
返回形狀縮圖。

### 返回

Shape thumbnail or None in case when ShapeThumbnailBounds.Appearance is used and a shape doesn't have visible elements.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/zh-hant/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | X 縮放 |
| scale_y | **float** | Y 縮放 |



### 參見
* 類別 [`IImage`](/slides/python-net/zh-hant/aspose.slides/iimage)
* 類別 [`PictureFrame`](/slides/python-net/zh-hant/aspose.slides/pictureframe)
* 列舉 [`ShapeThumbnailBounds`](/slides/python-net/zh-hant/aspose.slides/shapethumbnailbounds)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)