---
title: ExportHiddenSlides
second_title: Справочник по API Aspose.Slides для .NET
description: Определяет будут ли экспортироваться скрытые слайды.
type: docs
weight: 20
url: /ru/net/aspose.slides.export.xaml/xamloptions/exporthiddenslides/
---
## XamlOptions.ExportHiddenSlides property

Определяет, будут ли экспортироваться скрытые слайды.

```csharp
public bool ExportHiddenSlides { get; set; }
```

### Примеры

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Смотрите также

* class [XamlOptions](../../xamloptions)
* пространство имен [Aspose.Slides.Export.Xaml](../../xamloptions)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->