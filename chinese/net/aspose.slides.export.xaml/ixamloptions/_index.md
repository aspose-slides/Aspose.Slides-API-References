---
title: IXamlOptions
second_title: Aspose.Slides for .NET API 参考
description: 控制如何保存 XAML 文档的选项
type: docs
weight: 4270
url: /zh/net/aspose.slides.export.xaml/ixamloptions/
---
## IXamlOptions interface

控制如何保存 XAML 文档的选项。

```csharp
public interface IXamlOptions : ISaveOptions
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AsISaveOptions](../../aspose.slides.export.xaml/ixamloptions/asisaveoptions) { get; } | 返回 ISaveOptions 接口。 只读[`ISaveOptions`](../../aspose.slides.export/isaveoptions)。 |
| [ExportHiddenSlides](../../aspose.slides.export.xaml/ixamloptions/exporthiddenslides) { get; set; } | 确定是否导出隐藏的幻灯片。 |
| [OutputSaver](../../aspose.slides.export.xaml/ixamloptions/outputsaver) { get; set; } | 表示 IOutputSaver 接口的实现。 |

### 例子

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### 也可以看看

* interface [ISaveOptions](../../aspose.slides.export/isaveoptions)
* 命名空间 [Aspose.Slides.Export.Xaml](../../aspose.slides.export.xaml)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->