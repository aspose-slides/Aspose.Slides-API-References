---
title: compress_image method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/picturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
通过根据形状大小和指定的分辨率降低图像尺寸来压缩图像。可选地，它还会删除裁剪区域。

### 返回

一个 **bool**，指示图像是否成功压缩。如果图像已被调整大小或裁剪，则返回 **True**，否则返回 **False**。



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | 如果为 true，方法将删除图像的裁剪区域，可能进一步减小其大小。 |
| resolution | [`PicturesCompression`](/slides/python-net/zh/aspose.slides.export/picturescompression) | 用于压缩的目标分辨率，指定为 [`PicturesCompression`](/slides/python-net/zh/aspose.slides.export/picturescompression) 枚举的值。 |

### 备注

此方法会更改图像的尺寸和分辨率，类似于 PowerPoint 的 “Picture Format -> Compress Pictures” 功能。

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 当分辨率不是有效值时抛出。 |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
通过根据形状大小和指定的分辨率降低图像尺寸来压缩图像。可选地，它还会删除裁剪区域。

### 返回

一个 **bool**，指示图像是否成功压缩。如果图像已被调整大小或裁剪，则返回 **True**，否则返回 **False**。



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | 如果为 true，方法将删除图像的裁剪区域，可能进一步减小其大小。 |
| resolution | **float** | 目标分辨率，单位为 DPI。该值必须为正数，并定义图像将如何被重新调整大小。 |

### 备注

此方法会更改图像的尺寸和分辨率，类似于 PowerPoint 的 “Picture Format -> Compress Pictures” 功能。

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 当分辨率不是正值时抛出。 |



### 另见
* 类 [`PictureFillFormat`](/slides/python-net/zh/aspose.slides/picturefillformat)
* 枚举 [`PicturesCompression`](/slides/python-net/zh/aspose.slides.export/picturescompression)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)