---
title: SlidesLayoutOptions
second_title: Aspose.Slides для .NET API Справочник
description: Получает или задает режим, в котором слайды размещаются на странице при экспорте презентации ISlidesLayoutOptionsaspose.slides.export/islideslayoutoptions.
type: docs
weight: 70
url: /ru/aspose.slides.export/ihtml5options/slideslayoutoptions/
---

## IHtml5Options.SlidesLayoutOptions свойство

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

### Также смотрите

* интерфейс [ISlidesLayoutOptions](../../islideslayoutoptions)
* интерфейс [IHtml5Options](../../ihtml5options)
* пространство имен [Aspose.Slides.Export](../../ihtml5options)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->