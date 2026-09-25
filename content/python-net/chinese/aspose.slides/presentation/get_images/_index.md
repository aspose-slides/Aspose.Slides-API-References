---
title: get_images method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
返回 Image 对象，用于演示文稿的所有幻灯片。

### Returns

Image 对象。



```python
def get_images(self, options):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | Tiff 选项。 |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
返回 Thumbnail Image 对象，针对演示文稿的指定幻灯片。

### Returns

Thumbnail Image 对象。



```python
def get_images(self, options, slides):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | Tiff 选项。 |
| slides | **List[int]** | Array 包含幻灯片位置的数组，起始值为 1。 |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
返回 Thumbnail Image 对象，针对演示文稿的所有幻灯片，使用指定的大小。

### Returns

Thumbnail Image 对象。



```python
def get_images(self, options, image_size):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | Tiff 选项。 |
| image_size | [`Size`](/slides/python-net/zh/aspose.slides/size) | 要创建的 image 的大小。 |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
返回 Thumbnail Image 对象，针对演示文稿的所有幻灯片，使用自定义缩放。

### Returns

Thumbnail Image 对象。



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | Tiff 选项。 |
| scale_x | **float** | 用于在 x 轴方向缩放此 Thumbnail 的值。 |
| scale_y | **float** | 用于在 y 轴方向缩放此 Thumbnail 的值。 |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
返回 Thumbnail Image 对象，针对演示文稿的指定幻灯片，使用指定的大小。

### Returns

Thumbnail Image 对象。



```python
def get_images(self, options, slides, image_size):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | Tiff 选项。 |
| slides | **List[int]** | Array 包含幻灯片位置的数组，起始值为 1。 |
| image_size | [`Size`](/slides/python-net/zh/aspose.slides/size) | 要创建的 image 的大小。 |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
返回 Thumbnail Image 对象，针对演示文稿的指定幻灯片，使用自定义缩放。

### Returns

Thumbnail Image 对象。



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | Tiff 选项。 |
| slides | **List[int]** | Array 包含幻灯片位置的数组，起始值为 1。 |
| scale_x | **float** | 用于在 x 轴方向缩放此 Thumbnail 的值。 |
| scale_y | **float** | 用于在 y 轴方向缩放此 Thumbnail 的值。 |



### See Also
* 类 [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions)
* 类 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation)
* 类 [`Size`](/slides/python-net/zh/aspose.slides/size)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)