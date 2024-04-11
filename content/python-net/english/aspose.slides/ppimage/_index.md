---
title: PPImage
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/ppimage/
---


PPImage class

Represents an image in a presentation.

The PPImage type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [binary_data](/slides/python-net/aspose.slides/ppimage/binary_data/) | Returns the copy of an image's data.<br/>            Read-only <br/>.NET type System.Byte<br/>[]. |
| [system_image](/slides/python-net/aspose.slides/ppimage/system_image/) | Returns the copy of an image.<br/>            Read-only <br/>.NET type System.Drawing.Image<br/>. |
| [svg_image](/slides/python-net/aspose.slides/ppimage/svg_image/) | Returns or sets ISvgImage object <br/>[`ISvgImage`](/slides/python-net/aspose.slides/isvgimage) |
| [content_type](/slides/python-net/aspose.slides/ppimage/content_type/) | Returns a MIME type of an image, encoded in <br/>[`PPImage.binary_data`](/slides/python-net/aspose.slides/ppimage#binary_data)<br/>.<br/>            Read-only <br/>.NET type System.String<br/>. |
| [width](/slides/python-net/aspose.slides/ppimage/width/) | Returns a width of an image.<br/>            Read-only <br/>.NET type System.Int32<br/>. |
| [height](/slides/python-net/aspose.slides/ppimage/height/) | Returns a height of an image.<br/>            Read-only <br/>.NET type System.Int32<br/>. |
| [x](/slides/python-net/aspose.slides/ppimage/x/) | Returns a X-offset of an image.<br/>            Read-only <br/>.NET type System.Int32<br/>. |
| [y](/slides/python-net/aspose.slides/ppimage/y/) | Returns a Y-offset of an image.<br/>            Read-only <br/>.NET type System.Int32<br/>. |

## Methods

| Method | Description |
| :- | :- |
| [replace_image](/slides/python-net/aspose.slides/ppimage/ppimage/#bytes/) | Replaces image data.<br/>            <br/>The new image's data.<br/>When newImageData parameter is null. |
| [replace_image](/slides/python-net/aspose.slides/ppimage/ppimage/#aspose.pydrawing.Image/) | Replaces image data. Attention: when Image is metafile - it will be rasterized due to restrictions of GDI+. Use ReplaceImage(byte[]) instead<br/>            <br/>The new image.<br/>When newImage parameter is null. |
| [replace_image](/slides/python-net/aspose.slides/ppimage/ppimage/#IPPImage/) | Replaces image data.<br/>            <br/>The new IPPImage.<br/>When newImage parameter is null. |

