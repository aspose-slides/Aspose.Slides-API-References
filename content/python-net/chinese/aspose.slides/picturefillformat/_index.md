---
title: PictureFillFormat class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/picturefillformat/
---
## PictureFillFormat 类

表示一种图片填充样式。

**继承:**[`PictureFillFormat`](/slides/python-net/zh/aspose.slides/picturefillformat) → [`PVIObject`](/slides/python-net/zh/aspose.slides/pviobject)

PictureFillFormat 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`dpi`](/slides/python-net/zh/aspose.slides/picturefillformat/dpi/) | 返回或设置用于填充图片的 dpi。<br/>            可读写 **int**. |
| [`picture_fill_mode`](/slides/python-net/zh/aspose.slides/picturefillformat/picture_fill_mode/) | 返回或设置图片填充模式。<br/>            可读写 [`PictureFillMode`](/slides/python-net/zh/aspose.slides/picturefillmode). |
| [`picture`](/slides/python-net/zh/aspose.slides/picturefillformat/picture/) | 返回图片。<br/>            只读 [`ISlidesPicture`](/slides/python-net/zh/aspose.slides/islidespicture). |
| [`crop_left`](/slides/python-net/zh/aspose.slides/picturefillformat/crop_left/) | 返回或设置实际图像宽度的百分比，被裁剪掉的左侧部分。<br/>            只读 **float**. |
| [`crop_top`](/slides/python-net/zh/aspose.slides/picturefillformat/crop_top/) | 返回或设置实际图像高度的百分比，被裁剪掉的顶部部分。<br/>            可读写 **float**. |
| [`crop_right`](/slides/python-net/zh/aspose.slides/picturefillformat/crop_right/) | 返回或设置实际图像宽度的百分比，被裁剪掉的右侧部分。<br/>            可读写 **float**. |
| [`crop_bottom`](/slides/python-net/zh/aspose.slides/picturefillformat/crop_bottom/) | 返回或设置实际图像高度的百分比，被裁剪掉的底部部分。<br/>            可读写 **float**. |
| [`stretch_offset_left`](/slides/python-net/zh/aspose.slides/picturefillformat/stretch_offset_left/) | 返回或设置填充矩形的左边缘，该边缘由相对于形状边界框左边缘的百分比偏移定义。正百分比表示内缩，而负百分比表示外伸。<br/>            可读写 **float**. |
| [`stretch_offset_top`](/slides/python-net/zh/aspose.slides/picturefillformat/stretch_offset_top/) | 返回或设置填充矩形的上边缘，该边缘由相对于形状边界框上边缘的百分比偏移定义。正百分比表示内缩，而负百分比表示外伸。<br/>            可读写 **float**. |
| [`stretch_offset_right`](/slides/python-net/zh/aspose.slides/picturefillformat/stretch_offset_right/) | 返回或设置填充矩形的右边缘，该边缘由相对于形状边界框右边缘的百分比偏移定义。正百分比表示内缩，而负百分比表示外伸。<br/>            可读写 **float**. |
| [`stretch_offset_bottom`](/slides/python-net/zh/aspose.slides/picturefillformat/stretch_offset_bottom/) | 返回或设置填充矩形的下边缘，该边缘由相对于形状边界框下边缘的百分比偏移定义。正百分比表示内缩，而负百分比表示外伸。<br/>            可读写 **float**. |
| [`tile_offset_x`](/slides/python-net/zh/aspose.slides/picturefillformat/tile_offset_x/) | 返回或设置纹理相对于形状原点的水平偏移（单位为点）。正值将纹理向右移动，负值将纹理向左移动。<br/>            可读写 **float**. |
| [`tile_offset_y`](/slides/python-net/zh/aspose.slides/picturefillformat/tile_offset_y/) | 返回或设置纹理相对于形状原点的垂直偏移（单位为点）。正值将纹理向下移动，负值将纹理向上移动。<br/>            可读写 **float**. |
| [`tile_scale_x`](/slides/python-net/zh/aspose.slides/picturefillformat/tile_scale_x/) | 返回或设置纹理填充的水平比例，以百分比表示。<br/>            可读写 **float**. |
| [`tile_scale_y`](/slides/python-net/zh/aspose.slides/picturefillformat/tile_scale_y/) | 返回或设置纹理填充的垂直比例，以百分比表示。<br/>            可读写 **float**. |
| [`tile_alignment`](/slides/python-net/zh/aspose.slides/picturefillformat/tile_alignment/) | 返回或设置纹理在形状内的对齐方式。此设置控制纹理图案的起始点以及它在形状中的重复方式。<br/>            可读写 [`RectangleAlignment`](/slides/python-net/zh/aspose.slides/rectanglealignment). |
| [`tile_flip`](/slides/python-net/zh/aspose.slides/picturefillformat/tile_flip/) | 在水平、垂直或两者轴上翻转纹理平铺。<br/>            可读写 [`TileFlip`](/slides/python-net/zh/aspose.slides/tileflip). |
| [`slide`](/slides/python-net/zh/aspose.slides/picturefillformat/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/picturefillformat/presentation/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/zh/aspose.slides/picturefillformat/compress_image/#bool-asposeslidesexportpicturescompression) | 通过根据形状大小和指定的分辨率缩小图像尺寸来压缩图像。可选地，它还会删除裁剪区域。 |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/zh/aspose.slides/picturefillformat/compress_image/#bool-float) | 通过根据形状大小和指定的分辨率缩小图像尺寸来压缩图像。可选地，它还会删除裁剪区域。 |
| [`delete_picture_cropped_areas(self)`](/slides/python-net/zh/aspose.slides/picturefillformat/delete_picture_cropped_areas/#) | 删除填充图片的裁剪区域。 |

### 另见
* 类 [`PictureFillFormat`](/slides/python-net/zh/aspose.slides/picturefillformat)
* 类 [`PVIObject`](/slides/python-net/zh/aspose.slides/pviobject)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)