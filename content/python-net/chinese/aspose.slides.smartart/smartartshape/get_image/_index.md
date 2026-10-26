---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides.smartart/smartartshape/get_image/
weight: 50
---
## get_image(self) {#}
返回形状缩略图。
            ShapeThumbnailBounds.Shape 形状缩略图边界类型默认使用。

### 返回

形状缩略图。



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
返回形状缩略图。

### 返回

在使用 ShapeThumbnailBounds.Appearance 且形状没有可见元素的情况下返回形状缩略图或 None。



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/zh/aspose.slides/shapethumbnailbounds) | 形状缩略图边界类型。 |
| scale_x | **float** | X 缩放 |
| scale_y | **float** | Y 缩放 |



### 另请参阅
* 类 [`IImage`](/slides/python-net/zh/aspose.slides/iimage)
* 枚举 [`ShapeThumbnailBounds`](/slides/python-net/zh/aspose.slides/shapethumbnailbounds)
* 类 [`SmartArtShape`](/slides/python-net/zh/aspose.slides.smartart/smartartshape)
* 模块 [`aspose.slides.smartart`](/slides/python-net/zh/aspose.slides.smartart)
* 库 [`Aspose.Slides`](/slides/python-net)