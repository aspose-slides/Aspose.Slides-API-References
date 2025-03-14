---
title: TileScaleX
second_title: Aspose.Sildes for .NET API Reference
description: Returns or sets the horizontal scale for the texture fill as a percentage. Read/write Single.
type: docs
weight: 160
url: /aspose.slides/picturefillformat/tilescalex/
---

## PictureFillFormat.TileScaleX property

Returns or sets the horizontal scale for the texture fill as a percentage. Read/write Single.

```csharp
public float TileScaleX { get; set; }
```

### Examples

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    ISlide slide = presentation.Slides[0];

    // Gets the picture fill format of the shape
    IPictureFillFormat pictureFillFormat = slide.Shapes[0].FillFormat.PictureFillFormat;

    // Sets the picture fill mode to Tile
    pictureFillFormat.PictureFillMode = PictureFillMode.Tile;

    // Sets the horizontal scale for the texture to 120 percents
    pictureFillFormat.TileScaleX = 120;
}
```

### See Also

* class [PictureFillFormat](../../picturefillformat)
* namespace [Aspose.Slides](../../picturefillformat)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
