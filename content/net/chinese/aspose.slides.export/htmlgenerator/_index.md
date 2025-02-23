---
title: HtmlGenerator
second_title: Aspose.Slides for .NET API 参考
description: Html 生成器
type: docs
weight: 3560
url: /zh/aspose.slides.export/htmlgenerator/
---
## HtmlGenerator class

Html 生成器。

```csharp
public sealed class HtmlGenerator : IHtmlGenerator
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [NextSlideIndex](../../aspose.slides.export/htmlgenerator/nextslideindex) { get; } | 返回幻灯片的索引，它将在当前幻灯片之后呈现，如果当前呈现最后一张幻灯片，则为 -1。 只读Int32。 |
| [PreviousSlideIndex](../../aspose.slides.export/htmlgenerator/previousslideindex) { get; } | 返回先前渲染幻灯片的索引，如果正在渲染第一张幻灯片，则返回 -1。 只读Int32。 |
| [SlideImageSize](../../aspose.slides.export/htmlgenerator/slideimagesize) { get; } | 返回幻灯片图像大小。 只读SizeF。 |
| [SlideImageSizeUnit](../../aspose.slides.export/htmlgenerator/slideimagesizeunit) { get; } | 返回指定幻灯片图像大小的单位。 只读[`SvgCoordinateUnit`](../svgcoordinateunit)。 |
| [SlideImageSizeUnitCode](../../aspose.slides.export/htmlgenerator/slideimagesizeunitcode) { get; } | 返回指定幻灯片图像大小的单位 css 代码。 只读String。 |
| [SlideIndex](../../aspose.slides.export/htmlgenerator/slideindex) { get; } | 返回当前渲染幻灯片的索引。 只读Int32。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddAttributeValue](../../aspose.slides.export/htmlgenerator/addattributevalue#addattributevalue)(char[]) | 引用属性值并将其添加到 html 文件中。 |
| [AddAttributeValue](../../aspose.slides.export/htmlgenerator/addattributevalue#addattributevalue_2)(string) | 引用属性值并将其添加到 html 文件中。 |
| [AddAttributeValue](../../aspose.slides.export/htmlgenerator/addattributevalue#addattributevalue_1)(char[], int, int) | 引用属性值并将其添加到 html 文件中。 |
| [AddHtml](../../aspose.slides.export/htmlgenerator/addhtml#addhtml)(char[]) | 添加格式化的 HTML 文本。 |
| [AddHtml](../../aspose.slides.export/htmlgenerator/addhtml#addhtml_2)(string) | 添加格式化的 HTML 文本。 |
| [AddHtml](../../aspose.slides.export/htmlgenerator/addhtml#addhtml_1)(char[], int, int) | 添加格式化的 HTML 文本。 |
| [AddText](../../aspose.slides.export/htmlgenerator/addtext#addtext)(char[]) | 将纯文本添加到 html 文件，用 html 实体替换特殊字符。 换行符和空格不会被替换。 |
| [AddText](../../aspose.slides.export/htmlgenerator/addtext#addtext_2)(string) | 将纯文本添加到 html 文件，用 html 实体替换特殊字符。 换行符和空格不会被替换。 |
| [AddText](../../aspose.slides.export/htmlgenerator/addtext#addtext_1)(char[], int, int) | 将纯文本添加到 html 文件，用 html 实体替换特殊字符。 换行符和空格不会被替换。 |

### 也可以看看

* interface [IHtmlGenerator](../ihtmlgenerator)
* 命名空间 [Aspose.Slides.Export](../../aspose.slides.export)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
