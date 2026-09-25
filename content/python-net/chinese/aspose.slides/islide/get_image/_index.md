---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/islide/get_image/
weight: 40
---
## get_image(self) {#}
返回一个缩略图图像对象（实际尺寸的 20%）。

### 返回
图像对象 **aspose.slides.IImage**



```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposeslidessize}
返回具有指定大小的图像对象。

### 返回
位图对象。



```python
def get_image(self, image_size):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/zh/aspose.slides/size) | 要创建的图像的大小。 |


## get_image(self, options) {#asposeslidesexportitiffoptions}
返回具有指定参数的缩略图 tiff 位图对象。

### 返回
图像对象。



```python
def get_image(self, options):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/zh/aspose.slides.export/itiffoptions) | Tiff 选项。 |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
返回缩略图位图对象。

### 返回
位图对象。



```python
def get_image(self, options):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | 渲染选项。 |


## get_image(self, scale_x, scale_y) {#float-float}
返回具有自定义缩放的图像对象。

### 返回
图像对象 **aspose.slides.IImage**



```python
def get_image(self, scale_x, scale_y):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| scale_x | **float** | 在 x 轴方向上缩放此缩略图的值。 |
| scale_y | **float** | 在 y 轴方向上缩放此缩略图的值。 |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
返回具有指定大小的缩略图位图对象。

### 返回
位图对象。



```python
def get_image(self, options, image_size):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | 渲染选项。 |
| image_size | [`Size`](/slides/python-net/zh/aspose.slides/size) | 要创建的图像的大小。 |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
返回具有自定义缩放的缩略图位图对象。

### 返回
位图对象。



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | 渲染选项。 |
| scale_x | **float** | 在 x 轴方向上缩放此缩略图的值。 |
| scale_y | **float** | 在 y 轴方向上缩放此缩略图的值。 |


### 另见
* 类 [`IImage`](/slides/python-net/zh/aspose.slides/iimage)
* 类 [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions)
* 类 [`ISlide`](/slides/python-net/zh/aspose.slides/islide)
* 类 [`ITiffOptions`](/slides/python-net/zh/aspose.slides.export/itiffoptions)
* 类 [`Size`](/slides/python-net/zh/aspose.slides/size)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)