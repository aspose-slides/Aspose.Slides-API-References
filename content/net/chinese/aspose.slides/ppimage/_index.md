---
title: PPImage
second_title: Aspose.Sildes for .NET API Reference
description: 表示演示文稿中的图像。
type: docs
weight: 8980
url: /zh/aspose.slides/ppimage/
---

## PPImage class

表示演示文稿中的图像。

```csharp
public class PPImage : IDisposable, IPPImage
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [BinaryData](../../aspose.slides/ppimage/binarydata) { get; } | 返回图像数据的副本。仅限读取 Byte[]. |
| [ContentType](../../aspose.slides/ppimage/contenttype) { get; } | 返回图像的 MIME 类型，编码在 [`BinaryData`](./binarydata) 中。仅限读取 String。 |
| [Height](../../aspose.slides/ppimage/height) { get; } | 返回图像的高度。仅限读取 Int32。 |
| [Image](../../aspose.slides/ppimage/image) { get; } | 返回图像的副本。仅限读取 [`IImage`](../iimage)。 |
| [SvgImage](../../aspose.slides/ppimage/svgimage) { get; set; } | 返回或设置 ISvgImage 对象 [`ISvgImage`](../isvgimage) |
| [Width](../../aspose.slides/ppimage/width) { get; } | 返回图像的宽度。仅限读取 Int32。 |
| [X](../../aspose.slides/ppimage/x) { get; } | 返回图像的 X 偏移量。仅限读取 Int32。 |
| [Y](../../aspose.slides/ppimage/y) { get; } | 返回图像的 Y 偏移量。仅限读取 Int32。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../aspose.slides/ppimage/dispose)() | 释放对象。 |
| override [GetHashCode](../../aspose.slides/ppimage/gethashcode)() | 返回图像的哈希代码。 |
| [ReplaceImage](../../aspose.slides/ppimage/replaceimage#replaceimage_2)(byte[]) | 替换图像数据。新图像的数据。当 newImageData 参数为 null 时。 |
| [ReplaceImage](../../aspose.slides/ppimage/replaceimage#replaceimage)(IImage) | 替换图像数据。注意：当图像为元文件时，它将被栅格化。请改用 ReplaceImage(byte[])。新图像。当 newImage 参数为 null 时。 |
| [ReplaceImage](../../aspose.slides/ppimage/replaceimage#replaceimage_1)(IPPImage) | 替换图像数据。新的 IPPImage。当 newImage 参数为 null 时。 |

### 另请参见

* 接口 [IPPImage](../ippimage)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->