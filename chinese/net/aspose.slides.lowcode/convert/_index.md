---
title: Convert
second_title: Aspose.Slides for .NET API 参考
description: 表示一组用于转换Presentation../aspose.slides/presentation的方法
type: docs
weight: 7180
url: /zh/net/aspose.slides.lowcode/convert/
---
## Convert class

表示一组用于转换[`Presentation`](../../aspose.slides/presentation)的方法。

```csharp
public static class Convert
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [AutoByExtension](../../aspose.slides.lowcode/convert/autobyextension)(string, string) | 使用传递的输出路径扩展名转换[`Presentation`](../../aspose.slides/presentation)以确定所需的导出格式。 |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf)(Presentation, string) | 将[`Presentation`](../../aspose.slides/presentation)转换为 PDF。 |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_2)(string, string) | 将[`Presentation`](../../aspose.slides/presentation)转换为 PDF。 |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_1)(Presentation, string, IPdfOptions) | 将[`Presentation`](../../aspose.slides/presentation)转换为 PDF。 |
| static [ToPdf](../../aspose.slides.lowcode/convert/topdf#topdf_3)(string, string, IPdfOptions) | 将[`Presentation`](../../aspose.slides/presentation)转换为 PDF。 |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_3)(string) | 将[`Presentation`](../../aspose.slides/presentation)转换为 SVG。 |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_1)(Presentation, GetOutPathCallback) | 将[`Presentation`](../../aspose.slides/presentation)转换为 SVG。 |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg)(Presentation, ISVGOptions) | 将[`Presentation`](../../aspose.slides/presentation)转换为 SVG。 |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_4)(string, GetOutPathCallback) | 将[`Presentation`](../../aspose.slides/presentation)转换为 SVG。 |
| static [ToSvg](../../aspose.slides.lowcode/convert/tosvg#tosvg_2)(Presentation, GetOutPathCallback, ISVGOptions) | 将[`Presentation`](../../aspose.slides/presentation)转换为 SVG。 |

## 其他成员

| 姓名 | 描述 |
| --- | --- |
| delegate [GetOutPathCallback](convert.getoutpathcallback) |  |

### 例子

```csharp
Convert.AutoByExtension("pres.pptx", "pres.pdf");
```

### 也可以看看

* 命名空间 [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->