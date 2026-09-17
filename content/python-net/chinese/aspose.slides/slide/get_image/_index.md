---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
返回 Thumbnail Image 对象（实际大小的 20%）。


```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposepydrawingsize}
返回具有指定大小的 Thumbnail Image 对象。

### Returns

Image 对象。



```python
def get_image(self, image_size):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image_size | **aspose.slides.Size** | 要创建的图像的大小。 |


## get_image(self, options) {#asposeslidesexportitiffoptions}
返回具有指定参数的 Thumbnail tiff 图像对象。

### Returns

Image 对象。



```python
def get_image(self, options):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/zh/aspose.slides.export/itiffoptions) | Tiff 选项。 |

### Exceptions

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 当 options.SlideLayoutOption 为 NotesCommentsLayoutOptions 且其属性 NotesPosition 取值为 NotesPositions.BottomFull 时抛出。 |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
返回 Thumbnail Image 对象。

### Returns

Image 对象。



```python
def get_image(self, options):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | 渲染选项。 |

### Exceptions

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 当 notesCommentsLayouting.NotesPosition 取值为 NotesPositions.BottomFull 时抛出。 |


## get_image(self, scale_x, scale_y) {#float-float}
返回使用自定义缩放的 Thumbnail Image 对象。

### Returns

IImage 对象。



```python
def get_image(self, scale_x, scale_y):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| scale_x | **float** | 在 x 轴方向上缩放此 Thumbnail 的值。 |
| scale_y | **float** | 在 y 轴方向上缩放此 Thumbnail 的值。 |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
返回具有指定大小的 Thumbnail Image 对象。

### Returns

Image 对象。



```python
def get_image(self, options, image_size):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | 渲染选项。 |
| image_size | **aspose.slides.Size** | 要创建的图像的大小。 |

### Exceptions

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 当 options.SlideLayoutOption 为 NotesCommentsLayoutOptions 且其属性 NotesPosition 取值为 NotesPositions.BottomFull 时抛出。 |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
返回使用自定义缩放的 Thumbnail Image 对象。

### Returns

Bitmap 对象。



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | 渲染选项。 |
| scale_x | **float** | 在 x 轴方向上缩放此 Thumbnail 的值。 |
| scale_y | **float** | 在 y 轴方向上缩放此 Thumbnail 的值。 |

### Exceptions

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 当 notesCommentsLayouting.NotesPosition 取值为 NotesPositions.BottomFull 时抛出。 |



### 另见
* 类 [`IImage`](/slides/python-net/zh/aspose.slides/iimage)
* 类 [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions)
* 类 [`ITiffOptions`](/slides/python-net/zh/aspose.slides.export/itiffoptions)
* 类 [`Slide`](/slides/python-net/zh/aspose.slides/slide)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)