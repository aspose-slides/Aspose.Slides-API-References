---
title: ExportHiddenSlides
second_title: Aspose.Sildes for .NET API Reference
description: 确定是否导出隐藏幻灯片。默认值为 false。
type: docs
weight: 30
url: /zh/aspose.slides.export/igifoptions/exporthiddenslides/
---

## IGifOptions.ExportHiddenSlides 属性

确定是否导出隐藏幻灯片。默认值为 false。

```csharp
public bool ExportHiddenSlides { get; set; }
```

### 示例

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save("pres.gif", SaveFormat.Gif, new GifOptions { ExportHiddenSlides = false });
}
```

### 另见

* 接口 [IGifOptions](../../igifoptions)
* 命名空间 [Aspose.Slides.Export](../../igifoptions)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->