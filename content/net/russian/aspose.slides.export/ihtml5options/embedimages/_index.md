---
title: EmbedImages
second_title: Справка по API Aspose.Slides для .NET
description: Возвращает или задает параметр встраивания изображений. Чтение/запись логическое значение.
type: docs
weight: 50
url: /ru/aspose.slides.export/ihtml5options/embedimages/
---

## IHtml5Options.EmbedImages свойство

Возвращает или задает параметр встраивания изображений. Чтение/запись логическое значение.

```csharp
public bool EmbedImages { get; set; }
```

### Примеры

Пример:

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
  pres.Save("demo-linked-images.html", SaveFormat.Html5, new Html5Options()
  {
      EmbedImages = false
  });
}
```

### См. также

* интерфейс [IHtml5Options](../../ihtml5options)
* пространство имен [Aspose.Slides.Export](../../ihtml5options)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->