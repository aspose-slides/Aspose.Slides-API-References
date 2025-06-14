---
title: AddZoomFrame
second_title: Aspose.Slides für .NET API-Referenz
description: Fügt ein neues Zoom-Objekt am Ende einer Sammlung hinzu.
type: docs
weight: 220
url: /de/aspose.slides/shapecollection/addzoomframe/
---

## AddZoomFrame(float, float, float, float, ISlide) {#addzoomframe}

Fügt ein neues Zoom-Objekt am Ende einer Sammlung hinzu.

```csharp
public IZoomFrame AddZoomFrame(float x, float y, float width, float height, ISlide slide)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | Single | X-Koordinate eines neuen Zoom-Frames Single. |
| y | Single | Y-Koordinate eines neuen Zoom-Frames Single. |
| width | Single | Breite eines neuen Zoom-Frames Single. |
| height | Single | Höhe eines neuen Zoom-Frames Single. |
| slide | ISlide | Das Folienobjekt, auf das sich der Zoom-Frame bezieht [`ISlide`](../../islide). |

### Rückgabewert

Erstellt das Zoom-Objekt [`IZoomFrame`](../../izoomframe).

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Die referenzierte Folie gehört nicht zur aktuellen Präsentation. |

### Beispiele

Dieses Beispiel zeigt, wie man ein Zoom-Objekt am Ende einer Sammlung hinzufügt (angenommen, dass es mindestens zwei Folien in der Präsentation "Presentation.pptx" gibt):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1]);
}
```

### Siehe auch

* Schnittstelle [IZoomFrame](../../izoomframe)
* Schnittstelle [ISlide](../../islide)
* Klasse [ShapeCollection](../../shapecollection)
* Namespace [Aspose.Slides](../../shapecollection)
* Assembly [Aspose.Slides](../../../)

---

## AddZoomFrame(float, float, float, float, ISlide, IPPImage) {#addzoomframe_1}

Fügt ein neues Zoom-Objekt am Ende einer Sammlung hinzu.

```csharp
public IZoomFrame AddZoomFrame(float x, float y, float width, float height, ISlide slide, 
    IPPImage image)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | Single | X-Koordinate eines neuen Zoom-Frames Single. |
| y | Single | Y-Koordinate eines neuen Zoom-Frames Single. |
| width | Single | Breite eines neuen Zoom-Frames Single. |
| height | Single | Höhe eines neuen Zoom-Frames Single. |
| slide | ISlide | Das Folienobjekt, auf das sich der Zoom-Frame bezieht [`ISlide`](../../islide). |
| image | IPPImage | Das Bild für die referenzierte Folie [`IPPImage`](../../ippimage) |

### Rückgabewert

Erstellt das Zoom-Objekt [`IZoomFrame`](../../izoomframe).

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Die referenzierte Folie gehört nicht zur aktuellen Präsentation. |

### Beispiele

Dieses Beispiel zeigt, wie man ein Zoom-Objekt am Ende einer Sammlung hinzufügt (angenommen, dass es mindestens zwei Folien in der Präsentation "Presentation.pptx" gibt):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    IPPImage image = pres.Images.AddImage(Image.FromFile("image.png"));
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1], image);
}
```

### Siehe auch

* Schnittstelle [IZoomFrame](../../izoomframe)
* Schnittstelle [ISlide](../../islide)
* Schnittstelle [IPPImage](../../ippimage)
* Klasse [ShapeCollection](../../shapecollection)
* Namespace [Aspose.Slides](../../shapecollection)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->