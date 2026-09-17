---
title: get_images method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
返回演示文稿中所有幻灯片的缩略图图像对象。

### 返回

Bitmap 对象。

```python
def get_images(self, options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | 渲染选项。 |

## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
返回演示文稿中指定幻灯片的缩略图 Bitmap 对象。

### 返回

Bitmap 对象。

```python
def get_images(self, options, slides):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | 渲染选项。 |
| slides | **List[int]** | 包含幻灯片位置的数组，起始值为 1。 |

## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
返回演示文稿中所有幻灯片的缩略图图像对象，使用指定的大小。

### 返回

Bitmap 对象。

```python
def get_images(self, options, image_size):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | 渲染选项。 |
| image_size | **aspose.slides.Size** | 要创建的图像的大小。 |

## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
返回演示文稿中所有幻灯片的缩略图图像对象，使用自定义缩放。

### 返回

Bitmap 对象。

```python
def get_images(self, options, scale_x, scale_y):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | 渲染选项。 |
| scale_x | **float** | 在 x 轴方向上缩放此缩略图的比例值。 |
| scale_y | **float** | 在 y 轴方向上缩放此缩略图的比例值。 |

## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
返回演示文稿中指定幻灯片的缩略图图像对象，使用指定的大小。

### 返回

Bitmap 对象。

```python
def get_images(self, options, slides, image_size):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | 渲染选项。 |
| slides | **List[int]** | 包含幻灯片位置的数组，起始值为 1。 |
| image_size | **aspose.slides.Size** | 要创建的图像的大小。 |

## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
返回演示文稿中指定幻灯片的缩略图图像对象，使用自定义缩放。

### 返回

Bitmap 对象。

```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions) | 渲染选项。 |
| slides | **List[int]** | 包含幻灯片位置的数组，起始值为 1。 |
| scale_x | **float** | 在 x 轴方向上缩放此缩略图的比例值。 |
| scale_y | **float** | 在 y 轴方向上缩放此缩略图的比例值。 |

### 另请参阅
* 类 [`IPresentation`](/slides/python-net/zh/aspose.slides/ipresentation)
* 类 [`IRenderingOptions`](/slides/python-net/zh/aspose.slides.export/irenderingoptions)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)