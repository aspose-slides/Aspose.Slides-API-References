---
title: ExportHiddenSlides
second_title: Aspose.Sildes for .NET API Reference
description: Determines whether hidden slides will be exported. The default value is false.
type: docs
weight: 30
url: /aspose.slides.export/gifoptions/exporthiddenslides/
---

## GifOptions.ExportHiddenSlides property

Determines whether hidden slides will be exported. The default value is false.

```csharp
public bool ExportHiddenSlides { get; set; }
```

### Examples

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save("pres.gif", SaveFormat.Gif, new GifOptions { ExportHiddenSlides = false });
}
```

### See Also

* class [GifOptions](../../gifoptions)
* namespace [Aspose.Slides.Export](../../gifoptions)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
