---
title: RemoveUnusedMasterSlides
second_title: Référence de l'API Aspose.Slides pour .NET
description: Effectue la compression duPresentationaspose.slides/presentation en supprimant les diapositives principales inutilisées.
type: docs
weight: 20
url: /fr/net/aspose.slides.lowcode/compress/removeunusedmasterslides/
---
## Compress.RemoveUnusedMasterSlides method

Effectue la compression du[`Presentation`](../../../aspose.slides/presentation) en supprimant les diapositives principales inutilisées.

```csharp
public static void RemoveUnusedMasterSlides(Presentation pres)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| pres | Presentation | L'instance de présentation |

### Exemples

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(pres);
    
    pres.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

### Voir également

* class [Presentation](../../../aspose.slides/presentation)
* class [Compress](../../compress)
* espace de noms [Aspose.Slides.LowCode](../../compress)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->