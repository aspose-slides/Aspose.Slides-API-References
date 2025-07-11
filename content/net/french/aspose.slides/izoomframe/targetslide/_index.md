---
title: TargetSlide
second_title: Référence de l'API Aspose.Slides pour .NET
description: Obtient ou définit l'objet diapositive auquel l'objet Zoom de diapositive est lié. Lecture/écriture ISlideaspose.slides/islide.
type: docs
weight: 20
url: /fr/aspose.slides/izoomframe/targetslide/
---

## Propriété IZoomFrame.TargetSlide

Obtient ou définit l'objet diapositive auquel l'objet Zoom de diapositive est lié. Lecture/écriture [`ISlide`](../../islide).

```csharp
public ISlide TargetSlide { get; set; }
```

### Exemples

L'exemple suivant démontre comment changer la diapositive cible et crée une nouvelle image pour l'objet Zoom de diapositive :

```csharp
[C#]
IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1]);
zoomFrame.TargetSlide = pres.Slides[2];
```

### Voir aussi

* interface [ISlide](../../islide)
* interface [IZoomFrame](../../izoomframe)
* namespace [Aspose.Slides](../../izoomframe)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
