---
title: TileScaleX
second_title: Référence API Aspose.Slides pour .NET
description: Renvoie ou définit l'échelle horizontale pour le remplissage de texture en pourcentage. Lecture/écriture Single.
type: docs
weight: 160
url: /fr/aspose.slides/picturefillformat/tilescalex/
---

## Propriété PictureFillFormat.TileScaleX

Renvoie ou définit l'échelle horizontale pour le remplissage de texture en pourcentage. Lecture/écriture Single.

```csharp
public float TileScaleX { get; set; }
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

    // Définit l'échelle horizontale pour la texture à 120 pourcents
    pictureFillFormat.TileScaleX = 120;
}
```

### Voir aussi

* classe [PictureFillFormat](../../picturefillformat)
* espace de noms [Aspose.Slides](../../picturefillformat)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour Aspose.Slides.dll -->