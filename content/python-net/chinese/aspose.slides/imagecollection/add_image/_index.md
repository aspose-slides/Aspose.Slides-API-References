---
title: add_image method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/imagecollection/add_image/
weight: 10
---
## add_image(self, image_source) {#ippimage}
从另一个演示文稿中添加图像的副本。

### 返回

已添加的图像。

```python
def add_image(self, image_source):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage) | 源图像。 |
## add_image(self, image) {#iimage}
向演示文稿添加图像。

### 返回

已添加的图像。

```python
def add_image(self, image):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/zh/aspose.slides/iimage) | 要添加的图像。 |

### 备注

此方法在插入演示文稿之前，将 WMF/EMF 元文件转换为栅格 PNG 图像。

## add_image(self, stream) {#iorawiobase}
从流中向演示文稿添加图像。

### 返回

已添加的图像。

```python
def add_image(self, stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 用于添加图像的流。 |

### 备注

此方法可以在不将 WMF/EMF 元文件转换为栅格 PNG 图像的情况下将其添加到演示文稿中。

## add_image(self, buffer) {#bytes}
从指定的缓冲区向演示文稿添加图像。

### 返回

已添加的图像。

```python
def add_image(self, buffer):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| buffer | **bytes** | 缓冲区。 |
## add_image(self, svg_image) {#isvgimage}
从 Svg 对象向演示文稿添加图像。

### 返回

已添加的图像。

```python
def add_image(self, svg_image):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/zh/aspose.slides/isvgimage) | Svg 图像对象 [`ISvgImage`](/slides/python-net/zh/aspose.slides/isvgimage) |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 当 svgImage 参数为 None 时。 |
## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
从流中创建并添加图像到演示文稿。

### 返回

已添加 [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage)。

```python
def add_image(self, stream, loading_stream_behavior):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 用于添加图像文件的流。 |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/zh/aspose.slides/loadingstreambehavior) | 将应用于流的行为。 |

### 另见
* 类 [`IImage`](/slides/python-net/zh/aspose.slides/iimage)
* 类 [`ImageCollection`](/slides/python-net/zh/aspose.slides/imagecollection)
* 类 [`IPPImage`](/slides/python-net/zh/aspose.slides/ippimage)
* 类 [`ISvgImage`](/slides/python-net/zh/aspose.slides/isvgimage)
* 枚举 [`LoadingStreamBehavior`](/slides/python-net/zh/aspose.slides/loadingstreambehavior)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)