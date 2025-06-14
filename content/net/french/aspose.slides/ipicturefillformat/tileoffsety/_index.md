---
title: TileOffsetY
second_title: Référence de l'API Aspose.Slides pour .NET
description: Renvoie ou définit le décalage vertical de la texture par rapport à l'origine des formes en points. Une valeur positive déplace la texture vers le bas, tandis qu'une valeur négative la déplace vers le haut. Lecture/écriture Single.
type: docs
weight: 160
url: /fr/aspose.slides/ipicturefillformat/tileoffsety/
---

## Propriété IPictureFillFormat.TileOffsetY

Renvoie ou définit le décalage vertical de la texture par rapport à l'origine de la forme en points. Une valeur positive déplace la texture vers le bas, tandis qu'une valeur négative la déplace vers le haut. Lecture/écriture Single.

```csharp
public float TileOffsetY { get; set; }
```

### Exemples

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    ISlide slide = presentation.Slides[0];

    // Obtient le format de remplissage d'image de la forme
    IPictureFillFormat pictureFillFormat = slide.Shapes[0].FillFormat.PictureFillFormat;

    // Définit le mode de remplissage d'image sur Tile
    pictureFillFormat.PictureFillMode = PictureFillMode.Tile;

    // Définit le décalage vertical de la texture à -50 points
    pictureFillFormat.TileOffsetY = -50;
}
```

### Voir aussi

* interface [IPictureFillFormat](../../ipicturefillformat)
* namespace [Aspose.Slides](../../ipicturefillformat)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->