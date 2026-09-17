---
title: get_images method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
返回演示文稿所有幻灯片的 Image 对象。

### 返回

Image objects.



```python
def get_images(self, options):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | Tiff 选项。 |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
返回演示文稿中指定幻灯片的 Thumbnail Image 对象。

### 返回

Image objects.



```python
def get_images(self, options, slides):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | Tiff 选项。 |
| slides | **List[int]** | 包含幻灯片位置的数组，起始位置为 1。 |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
返回演示文稿所有幻灯片的 Thumbnail Image 对象，指定大小。

### 返回

Image objects.



```python
def get_images(self, options, image_size):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | Tiff 选项。 |
| image_size | **aspose.slides.Size** | 要创建的图像大小。 |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
返回演示文稿所有幻灯片的 Thumbnail Image 对象，自定义缩放。

### 返回

Image objects.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | Tiff 选项。 |
| scale_x | **float** | 在 x 轴方向上缩放此缩略图的值。 |
| scale_y | **float** | 在 y 轴方向上缩放此缩略图的值。 |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
返回演示文稿中指定幻灯片的 Thumbnail Image 对象，指定大小。

### 返回

Image objects.



```python
def get_images(self, options, slides, image_size):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | Tiff 选项。 |
| slides | **List[int]** | 包含幻灯片位置的数组，起始位置为 1。 |
| image_size | **aspose.slides.Size** | 要创建的图像大小。 |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
返回演示文稿中指定幻灯片的 Thumbnail Image 对象，自定义缩放。

### 返回

Image objects.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | Tiff 选项。 |
| slides | **List[int]** | 包含幻灯片位置的数组，起始位置为 1。 |
| scale_x | **float** | 在 x 轴方向上缩放此缩略图的值。 |
| scale_y | **float** | 在 y 轴方向上缩放此缩略图的值。 |



### 另请参见
* 类 [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions)
* 类 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)