---
title: SlidesLayoutOptions
second_title: Aspose.Slides pour l'API .NET Référence
description: Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation ISlidesLayoutOptionsaspose.slides.export/islideslayoutoptions.
type: docs
weight: 70
url: /fr/aspose.slides.export/ihtml5options/slideslayoutoptions/
---

## IHtml5Options.SlidesLayoutOptions propriété

Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [`ISlidesLayoutOptions`](../../islideslayoutoptions).

```csharp
public ISlidesLayoutOptions SlidesLayoutOptions { get; set; }
```

### Exemples

Exemple:

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

### Voir Aussi

* interface [ISlidesLayoutOptions](../../islideslayoutoptions)
* interface [IHtml5Options](../../ihtml5options)
* namespace [Aspose.Slides.Export](../../ihtml5options)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->