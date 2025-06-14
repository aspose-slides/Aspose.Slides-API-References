---
title: SlidesLayoutOptions
second_title: Aspose.Slides для .NET API Справочник
description: Получает или устанавливает режим, в котором слайды размещаются на странице при экспорте презентации ISlidesLayoutOptionsaspose.slides.export/islideslayoutoptions.
type: docs
weight: 100
url: /ru/aspose.slides.export/ihtmloptions/slideslayoutoptions/
---

## IHtmlOptions.SlidesLayoutOptions свойство

Получает или устанавливает режим, в котором слайды размещаются на странице при экспорте презентации [`ISlidesLayoutOptions`](../../islideslayoutoptions).

```csharp
public ISlidesLayoutOptions SlidesLayoutOptions { get; set; }
```

### Примеры

Пример:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    HtmlOptions options = new HtmlOptions
    {
        SlidesLayoutOptions = new HandoutLayoutingOptions
        {
            Handout = HandoutType.Handouts4Horizontal,
        }
    };
    
    pres.Save("pres.html", SaveFormat.Html, options);
}
```

### Смотрите также

* интерфейс [ISlidesLayoutOptions](../../islideslayoutoptions)
* интерфейс [IHtmlOptions](../../ihtmloptions)
* пространство имен [Aspose.Slides.Export](../../ihtmloptions)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->