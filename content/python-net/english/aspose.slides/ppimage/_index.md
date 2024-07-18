---
title: PPImage class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ppimage/
---


## PPImage class

Represents an image in a presentation.

The PPImage type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`binary_data`](/slides/python-net/aspose.slides/ppimage/binary_data/) | Returns the copy of an image's data.<br/>            Read-only **int**[]. |
| [`system_image`](/slides/python-net/aspose.slides/ppimage/system_image/) | Returns the copy of an image.<br/>            Read-only [`PPImage.image`](/slides/python-net/aspose.slides/ppimage/image). |
| [`image`](/slides/python-net/aspose.slides/ppimage/image/) | Returns the copy of an image.<br/>            Read-only [`IImage`](/slides/python-net/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/aspose.slides/ppimage/svg_image/) | Returns or sets ISvgImage object [`ISvgImage`](/slides/python-net/aspose.slides/isvgimage) |
| [`content_type`](/slides/python-net/aspose.slides/ppimage/content_type/) | Returns a MIME type of an image, encoded in [`PPImage.binary_data`](/slides/python-net/aspose.slides/ppimage/binary_data).<br/>            Read-only **str**. |
| [`width`](/slides/python-net/aspose.slides/ppimage/width/) | Returns a width of an image.<br/>            Read-only **int**. |
| [`height`](/slides/python-net/aspose.slides/ppimage/height/) | Returns a height of an image.<br/>            Read-only **int**. |
| [`x`](/slides/python-net/aspose.slides/ppimage/x/) | Returns a X-offset of an image.<br/>            Read-only **int**. |
| [`y`](/slides/python-net/aspose.slides/ppimage/y/) | Returns a Y-offset of an image.<br/>            Read-only **int**. |

## Methods

| Method | Description |
| :- | :- |
| [`replace_image`](/slides/python-net/aspose.slides/ppimage/replace_image/#bytes) | Replaces image data.<br/>The new image's data.When newImageData parameter is null. |
| [`replace_image`](/slides/python-net/aspose.slides/ppimage/replace_image/#asposepydrawingimage) | Replaces image data. Attention: when Image is metafile - it will be rasterized due to restrictions of GDI+. Use ReplaceImage(byte[]) instead<br/>The new image.When newImage parameter is null. |
| [`replace_image`](/slides/python-net/aspose.slides/ppimage/replace_image/#iimage) | Replaces image data. Attention: when Image is metafile - it will be rasterized. Use ReplaceImage(byte[]) instead<br/>The new image.When newImage parameter is null. |
| [`replace_image`](/slides/python-net/aspose.slides/ppimage/replace_image/#ippimage) | Replaces image data.<br/>The new IPPImage.When newImage parameter is null. |


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

