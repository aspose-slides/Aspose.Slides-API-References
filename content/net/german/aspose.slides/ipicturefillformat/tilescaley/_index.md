---  
title: TileScaleY
second_title: Aspose.Slides für .NET API Referenz  
description: Gibt den vertikalen Maßstab für die Texturfüllung als Prozentsatz zurück oder setzt ihn. Lese-/schreibbare Single.
type: docs
weight: 180  
url: /de/aspose.slides/ipicturefillformat/tilescaley/
---  

## IPictureFillFormat.TileScaleY-Eigenschaft  

Gibt den vertikalen Maßstab für die Texturfüllung als Prozentsatz zurück oder setzt ihn. Lese-/schreibbare Single.  

```csharp  
public float TileScaleY { get; set; }  
```  

### Beispiele  

```csharp  
[C#]  
using (Presentation presentation = new Presentation("demo.pptx"))  
{  
    ISlide slide = presentation.Slides[0];  

    // Ruft das Bildfüllformat der Form ab  
    IPictureFillFormat pictureFillFormat = slide.Shapes[0].FillFormat.PictureFillFormat;  

    // Setzt den Bildfüllmodus auf Tile  
    pictureFillFormat.PictureFillMode = PictureFillMode.Tile;  

    // Setzt den vertikalen Maßstab für die Textur auf 120 Prozent  
    pictureFillFormat.TileScaleY = 120;  
}  
```  

### Siehe Auch  

* Schnittstelle [IPictureFillFormat](../../ipicturefillformat)  
* Namespace [Aspose.Slides](../../ipicturefillformat)  
* Assembly [Aspose.Slides](../../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  