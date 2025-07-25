---
title: RemoveUnusedLayoutSlides
second_title: Aspose.Slides для .NET API Reference
description: Выполняет сжатие презентации aspose.slides/presentation, удаляя неиспользуемые макеты слайдов.
type: docs
weight: 20
url: /ru/aspose.slides.lowcode/compress/removeunusedlayoutslides/
---

## Compress.RemoveUnusedLayoutSlides метод

Выполняет сжатие [`Presentation`](../../../aspose.slides/presentation), удаляя неиспользуемые макеты слайдов.

```csharp
public static void RemoveUnusedLayoutSlides(Presentation pres)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | Presentation | Экземпляр презентации |

### Примеры

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(pres);
    
    pres.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

### См. также

* класс [Presentation](../../../aspose.slides/presentation)
* класс [Compress](../../compress)
* пространство имен [Aspose.Slides.LowCode](../../compress)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->