---
title: SlidesLayoutOptions
second_title: Aspose.Sildes для .NET API Reference
description: Получает или задает режим, в котором слайды размещаются на странице при экспорте презентации ISlidesLayoutOptionsaspose.slides.export/islideslayoutoptions.
type: docs
weight: 70
url: /ru/aspose.slides.export/ihtml5options/slideslayoutoptions/
---

## IHtml5Options.SlidesLayoutOptions property

Получает или задает режим, в котором слайды размещаются на странице при экспорте презентации [`ISlidesLayoutOptions`](../../islideslayoutoptions).

```csharp
public ISlidesLayoutOptions SlidesLayoutOptions { get; set; }
```

### Примеры

Пример:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    Html5Options options = new Html5Options
    {
        SlidesLayoutOptions = new HandoutLayoutingOptions
        {
            Handout = HandoutType.Handouts4Horizontal
        }
    };
    
    pres.Save("pres.html", SaveFormat.Html5, options);
}
```

### Смотрите также

* интерфейс [ISlidesLayoutOptions](../../islideslayoutoptions)
* интерфейс [IHtml5Options](../../ihtml5options)
* пространство имен [Aspose.Slides.Export](../../ihtml5options)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->