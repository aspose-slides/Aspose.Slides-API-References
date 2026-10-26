---
title: PPImage class
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides/ppimage/
---
## PPImage 类

表示演示文稿中的图像。

PPImage 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`binary_data`](/slides/python-net/zh/aspose.slides/ppimage/binary_data/) | 返回图像数据的副本。<br/>            只读 **int**[]. |
| [`image`](/slides/python-net/zh/aspose.slides/ppimage/image/) | 返回图像的副本。<br/>            只读 [`IImage`](/slides/python-net/zh/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/zh/aspose.slides/ppimage/svg_image/) | 返回或设置 ISvgImage 对象 [`ISvgImage`](/slides/python-net/zh/aspose.slides/isvgimage) |
| [`content_type`](/slides/python-net/zh/aspose.slides/ppimage/content_type/) | 返回图像的 MIME 类型，使用 [`PPImage.binary_data`](/slides/python-net/zh/aspose.slides/ppimage/binary_data) 编码。<br/>            只读 **str**. |
| [`width`](/slides/python-net/zh/aspose.slides/ppimage/width/) | 返回图像的宽度。<br/>            只读 **int**. |
| [`height`](/slides/python-net/zh/aspose.slides/ppimage/height/) | 返回图像的高度。<br/>            只读 **int**. |
| [`x`](/slides/python-net/zh/aspose.slides/ppimage/x/) | 返回图像的 X 偏移。<br/>            只读 **int**. |
| [`y`](/slides/python-net/zh/aspose.slides/ppimage/y/) | 返回图像的 Y 偏移。<br/>            只读 **int**. |

## 方法

| Method | Description |
| :- | :- |
| [`replace_image(self, new_image_data)`](/slides/python-net/zh/aspose.slides/ppimage/replace_image/#bytes) | 替换图像数据。<br/>            新图像的数据。当 newImageData 参数为 None 时。 |
| [`replace_image(self, new_image)`](/slides/python-net/zh/aspose.slides/ppimage/replace_image/#iimage) | 替换图像数据。注意：当 Image 为元文件时 - 它将被光栅化。请改用 ReplaceImage(byte[])。<br/>            新图像。当 newImage 参数为 None 时。 |
| [`replace_image(self, new_image)`](/slides/python-net/zh/aspose.slides/ppimage/replace_image/#ippimage) | 替换图像数据。<br/>            新的 IPPImage。当 newImage 参数为 None 时。 |

### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)