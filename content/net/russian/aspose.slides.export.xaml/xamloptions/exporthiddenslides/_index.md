---
title: ExportHiddenSlides
second_title: Aspose.Slides для .NET Справочник по API
description: Определяет, будут ли экспортироваться скрытые слайды.
type: docs
weight: 20
url: /ru/aspose.slides.export.xaml/xamloptions/exporthiddenslides/
---

## Свойство XamlOptions.ExportHiddenSlides

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

### См. также

* класс [XamlOptions](../../xamloptions)
* пространство имен [Aspose.Slides.Export.Xaml](../../xamloptions)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->