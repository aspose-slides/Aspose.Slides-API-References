---
title: ExportHiddenSlides
second_title: Справочник по API Aspose.Slides для .NET
description: Определяет будут ли экспортироваться скрытые слайды. Значение по умолчанию  false.
type: docs
weight: 30
url: /ru/net/aspose.slides.export/igifoptions/exporthiddenslides/
---
## IGifOptions.ExportHiddenSlides property

Определяет, будут ли экспортироваться скрытые слайды. Значение по умолчанию — false.

```csharp
public bool ExportHiddenSlides { get; set; }
```

### Примеры

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save("pres.gif", SaveFormat.Gif, new GifOptions { ExportHiddenSlides = false });
}
```

### Смотрите также

* interface [IGifOptions](../../igifoptions)
* пространство имен [Aspose.Slides.Export](../../igifoptions)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->