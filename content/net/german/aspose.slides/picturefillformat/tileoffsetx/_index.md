---
title: TileOffsetX
second_title: Aspose.Slides für .NET API-Referenz
description: Gibt den horizontalen Versatz der Textur vom Ursprungsort der Formen in Punkten zurück oder setzt ihn. Ein positiver Wert verschiebt die Textur nach rechts, während ein negativer Wert sie nach links verschiebt. Lesen/Schreiben Einzel.
type: docs
weight: 140
url: /de/aspose.slides/picturefillformat/tileoffsetx/
---

## PictureFillFormat.TileOffsetX-Eigenschaft

Gibt den horizontalen Versatz der Textur vom Ursprungsort der Form in Punkten zurück oder setzt ihn. Ein positiver Wert verschiebt die Textur nach rechts, während ein negativer Wert sie nach links verschiebt. Lesen/Schreiben Einzel.

```csharp
public float TileOffsetX { get; set; }
```

### Beispiele

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    ISlide slide = presentation.Slides[0];

    // Holt das Bildfüllformat der Form
    IPictureFillFormat pictureFillFormat = slide.Shapes[0].FillFormat.PictureFillFormat;

    // Setzt den Bildfüllmodus auf Fliesen
    pictureFillFormat.PictureFillMode = PictureFillMode.Tile;

    // Setzt den horizontalen Versatz der Textur auf 20 Punkte
    pictureFillFormat.TileOffsetX = 20f;
}
```

### Siehe auch

* Klasse [PictureFillFormat](../../picturefillformat)
* Namespace [Aspose.Slides](../../picturefillformat)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->