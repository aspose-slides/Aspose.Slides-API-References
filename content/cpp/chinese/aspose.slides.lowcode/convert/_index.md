---
title: Convert
second_title: Aspose.Slides for C++ API 参考
description: 表示一组用于转换 Presentation 的方法。
type: docs
weight: 27
url: /zh/aspose.slides.lowcode/convert/
---
## 转换类

Represents a group of methods intended to convert [Presentation](../../aspose.slides/presentation/).

```cpp
class Convert
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static void [AutoByExtension](./autobyextension/)([System::String](../../system/string/), [System::String](../../system/string/)) | 使用传入的输出路径扩展名来确定所需的导出格式，以转换 [Presentation](../../aspose.slides/presentation/)。 |
|  [Convert](./convert/)() |  |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | 将输入演示文稿转换为一组 JPEG 格式的图像。

 如果输出文件名为 "myPath/myFilename.jpeg"，结果将保存为一组 "myPath/myFilename_N.jpeg" 文件，其中 N 为幻灯片编号。 |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | 将输入演示文稿转换为一组 JPEG 格式的图像。

 如果输出文件名为 "myPath/myFilename.jpeg"，结果将保存为一组 "myPath/myFilename_N.jpeg" 文件，其中 N 为幻灯片编号。 |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | 将输入演示文稿转换为一组 JPEG 格式的图像。

 如果输出文件名为 "myPath/myFilename.jpeg"，结果将保存为一组 "myPath/myFilename_N.jpeg" 文件，其中 N 为幻灯片编号。 |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/)) | 将 [Presentation](../../aspose.slides/presentation/) 转换为 PDF。 |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | 将 [Presentation](../../aspose.slides/presentation/) 转换为 PDF。 |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | 将 [Presentation](../../aspose.slides/presentation/) 转换为 PDF。 |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | 将 [Presentation](../../aspose.slides/presentation/) 转换为 PDF。 |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | 将输入演示文稿转换为一组 PNG 格式的图像。

 如果输出文件名为 "myPath/myFilename.png"，结果将保存为一组 "myPath/myFilename_N.png" 文件，其中 N 为幻灯片编号。 |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | 将输入演示文稿转换为一组 PNG 格式的图像。

 如果输出文件名为 "myPath/myFilename.png"，结果将保存为一组 "myPath/myFilename_N.png" 文件，其中 N 为幻灯片编号。 |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | 将输入演示文稿转换为一组 PNG 格式的图像。

 如果输出文件名为 "myPath/myFilename.png"，结果将保存为一组 "myPath/myFilename_N.png" 文件，其中 N 为幻灯片编号。 |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/)) | 将 [Presentation](../../aspose.slides/presentation/) 转换为 SVG。 |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/), [Convert::GetOutPathCallback](./getoutpathcallback/)) | 将 [Presentation](../../aspose.slides/presentation/) 转换为 SVG。 |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/)) | 将 [Presentation](../../aspose.slides/presentation/) 转换为 SVG。 |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | 将 [Presentation](../../aspose.slides/presentation/) 转换为 SVG。 |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | 将 [Presentation](../../aspose.slides/presentation/) 转换为 SVG。 |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | 将输入演示文稿转换为一组 TIFF 格式的图像。

 如果输出文件名为 "myPath/myFilename.tiff"，结果将保存为一组 "myPath/myFilename_N.tiff" 文件，其中 N 为幻灯片编号。 |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>, **bool**) | 使用自定义选项将输入演示文稿转换为 TIFF 格式。如果输出文件名为 "myPath/myFilename.tiff" 且 *multipage* 为 **false**，结果将保存为一组 "myPath/myFilename_N.tiff" 文件，其中 N 为幻灯片编号。否则，如果 *multipage* 为 **true**，结果将是一个多页的 "myPath/myFilename.tiff" 文档。 |

## 类型定义

| 类型定义 | 描述 |
| --- | --- |
| [GetOutPathCallback](./getoutpathcallback/) | 将在每个 [Slide](../../aspose.slides/slide/) 上调用的回调，期望返回输出路径。 |

## 备注

```cpp
Convert::AutoByExtension(u"pres.pptx", u"pres.pdf");
```

## 另见

* 命名空间 [Aspose::Slides::LowCode](../)
* 库 [Aspose.Slides](../../)