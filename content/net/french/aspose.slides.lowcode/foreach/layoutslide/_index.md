---
title: LayoutSlide
second_title: Référence de l'API Aspose.Slides pour .NET
description: Itérer chaque LayoutSlide aspose.slides.lowcode/foreach/layoutslide dans la Presentation aspose.slides/presentation.
type: docs
weight: 10
url: /fr/aspose.slides.lowcode/foreach/layoutslide/
---

## Méthode ForEach.LayoutSlide

Itérer chaque `LayoutSlide` dans la [`Presentation`](../../../aspose.slides/presentation).

```csharp
public static void LayoutSlide(Presentation pres, ForEachLayoutSlideCallback forEachLayoutSlide)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pres | Presentation | Présentation pour itérer les diapositives de mise en page |
| forEachLayoutSlide | ForEachLayoutSlideCallback | Callback qui sera invoqué pour chaque diapositive de mise en page |

### Exemples

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    ForEach.LayoutSlide(pres, (layoutSlide, index) =>
    {
        layoutSlide.Name = $"LayoutSlide #{index}";
    });
} 
```

### Voir Aussi

* class [Presentation](../../../aspose.slides/presentation)
* delegate [ForEachLayoutSlideCallback](../../foreach.foreachlayoutslidecallback)
* class [ForEach](../../foreach)
* namespace [Aspose.Slides.LowCode](../../foreach)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->