---
title: SlidesLayoutOptions
second_title: Référence API Aspose.Slides pour .NET
description: Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation ISlidesLayoutOptionsaspose.slides.export/islideslayoutoptions.
type: docs
weight: 40
url: /fr/aspose.slides.export/renderingoptions/slideslayoutoptions/
---

## Propriété RenderingOptions.SlidesLayoutOptions

Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [`ISlidesLayoutOptions`](../../islideslayoutoptions).

```csharp
public ISlidesLayoutOptions SlidesLayoutOptions { get; set; }
```

### Exemples

Exemple :

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    RenderingOptions options = new RenderingOptions
    {
        SlidesLayoutOptions = new HandoutLayoutingOptions
        {
            Handout = HandoutType.Handouts4Horizontal,
            PrintSlideNumbers = false
        }
    };
    
    Bitmap[] handoutSlides = pres.GetThumbnails(options);
    for (var index = 0; index < handoutSlides.Length; index++)
    {
        var handoutSllide = handoutSlides[index];
        handoutSllide.Save($"handout-{index}.png");
    }
}
```

### Voir aussi

* interface [ISlidesLayoutOptions](../../islideslayoutoptions)
* classe [RenderingOptions](../../renderingoptions)
* espace de noms [Aspose.Slides.Export](../../renderingoptions)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS ÉDITER : généré par xmldocmd pour Aspose.Slides.dll -->