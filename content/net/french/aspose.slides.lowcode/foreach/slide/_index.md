---
title: Slide
second_title: Référence de l'API Aspose.Slides pour .NET
description: Itérer chaque Slide dans la Presentationaspose.slides/../aspose.slides/presentation.
type: docs
weight: 60
url: /fr/aspose.slides.lowcode/foreach/slide/
---

## Méthode ForEach.Slide

Itérer chaque `Slide` dans la [`Presentation`](../../../aspose.slides/presentation).

```csharp
public static void Slide(Presentation pres, ForEachSlideCallback forEachSlide)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pres | Presentation | Présentation à itérer les diapositives |
| forEachSlide | ForEachSlideCallback | Callback qui sera invoqué pour chaque diapositive |

### Exemples

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    ForEach.Slide(pres, (slide, index) =>
    {
        slide.Name = $"Slide #{index}";
    });
} 
```

### Voir aussi

* class [Presentation](../../../aspose.slides/presentation)
* delegate [ForEachSlideCallback](../../foreach.foreachslidecallback)
* class [ForEach](../../foreach)
* namespace [Aspose.Slides.LowCode](../../foreach)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->