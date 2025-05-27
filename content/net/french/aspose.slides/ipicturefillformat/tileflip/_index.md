---
title: TileFlip
second_title: Référence de l'API Aspose.Slides pour .NET
description: Retourne le carreau de texture autour de son axe horizontal, vertical ou des deux. Lecture/écriture de TileFlipaspose.slides/tileflip.
type: docs
weight: 140
url: /fr/aspose.slides/ipicturefillformat/tileflip/
---

## Propriété IPictureFillFormat.TileFlip

Retourne le carreau de texture autour de son axe horizontal, vertical ou des deux. Lecture/écriture de [`TileFlip`](../../tileflip).

```csharp
public TileFlip TileFlip { get; set; }
```

### Remarques

Par défaut, c'est NoFlip.

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

    // Retourne le carreau de texture autour de son axe vertical.
    pictureFillFormat.TileFlip = TileFlip.FlipY;
}
```

### Voir aussi

* enum [TileFlip](../../tileflip)
* interface [IPictureFillFormat](../../ipicturefillformat)
* namespace [Aspose.Slides](../../ipicturefillformat)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS ÉDITER : généré par xmldocmd pour Aspose.Slides.dll -->