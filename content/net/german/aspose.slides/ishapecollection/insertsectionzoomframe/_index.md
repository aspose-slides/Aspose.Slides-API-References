---
title: InsertSectionZoomFrame
second_title: Aspose.Slides für .NET API Referenz
description: Erstellt ein neues Section Zoom-Objekt und fügt es in eine Sammlung am angegebenen Index ein.
type: docs
weight: 320
url: /de/aspose.slides/ishapecollection/insertsectionzoomframe/
---

## InsertSectionZoomFrame(int, float, float, float, float, ISection) {#insertsectionzoomframe}

Erstellt ein neues Section Zoom-Objekt und fügt es in eine Sammlung am angegebenen Index ein.

```csharp
public ISectionZoomFrame InsertSectionZoomFrame(int index, float x, float y, float width, 
    float height, ISection section)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Der nullbasierte Index, an dem der Section Zoom-Frame eingefügt werden soll. |
| x | Single | X-Koordinate eines neuen Section Zoom-Frames Single. |
| y | Single | Y-Koordinate eines neuen Section Zoom-Frames Single. |
| width | Single | Breite eines neuen Section Zoom-Frames Single. |
| height | Single | Höhe eines neuen Section Zoom-Frames Single. |
| section | ISection | Das Folienobjekt, auf das der Section Zoom-Frame verweist [`ISection`](../../isection). |

### Rückgabewert

Erstelltes Section Zoom-Objekt [`ISectionZoomFrame`](../../isectionzoomframe).

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Die referenzierte Sektion gehört nicht zur aktuellen Präsentation oder enthält keine Folien. |

### Beispiele

Dieses Beispiel demonstriert die Erstellung und das Einfügen eines Section Zoom-Objekts am angegebenen Index einer Sammlung (angenommen, es gibt mindestens zwei Sektionen in der Präsentation "Presentation.pptx"):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    ISectionZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertSectionZoomFrame(2, 150, 20, 50, 50, pres.Sections[1]);
}
```

### Siehe auch

* Schnittstelle [ISectionZoomFrame](../../isectionzoomframe)
* Schnittstelle [ISection](../../isection)
* Schnittstelle [IShapeCollection](../../ishapecollection)
* Namespace [Aspose.Slides](../../ishapecollection)
* Assembly [Aspose.Slides](../../../)

---

## InsertSectionZoomFrame(int, float, float, float, float, ISection, IPPImage) {#insertsectionzoomframe_1}

Erstellt ein neues Section Zoom-Objekt und fügt es in eine Sammlung am angegebenen Index ein.

```csharp
public ISectionZoomFrame InsertSectionZoomFrame(int index, float x, float y, float width, 
    float height, ISection section, IPPImage image)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Der nullbasierte Index, an dem der Section Zoom-Frame eingefügt werden soll. |
| x | Single | X-Koordinate eines neuen Section Zoom-Frames Single. |
| y | Single | Y-Koordinate eines neuen Section Zoom-Frames Single. |
| width | Single | Breite eines neuen Section Zoom-Frames Single. |
| height | Single | Höhe eines neuen Section Zoom-Frames Single. |
| section | ISection | Das Folienobjekt, auf das der Section Zoom-Frame verweist [`ISection`](../../isection). |
| image | IPPImage | Das Bild für die referenzierte Folie [`IPPImage`](../../ippimage) |

### Rückgabewert

Erstelltes Section Zoom-Objekt [`ISectionZoomFrame`](../../isectionzoomframe).

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Die referenzierte Sektion gehört nicht zur aktuellen Präsentation oder enthält keine Folien. |

### Beispiele

Dieses Beispiel demonstriert die Erstellung und das Einfügen eines Section Zoom-Objekts am angegebenen Index einer Sammlung (angenommen, es gibt mindestens zwei Sektionen in der Präsentation "Presentation.pptx"):

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    IPPImage image = pres.Images.AddImage(Image.FromFile("image.png"));
    ISectionZoomFrame zoomFrame = pres.Slides[0].Shapes.InsertSectionZoomFrame(2, 150, 20, 50, 50, pres.Sections[1], image);
}
```

### Siehe auch

* Schnittstelle [ISectionZoomFrame](../../isectionzoomframe)
* Schnittstelle [ISection](../../isection)
* Schnittstelle [IPPImage](../../ippimage)
* Schnittstelle [IShapeCollection](../../ishapecollection)
* Namespace [Aspose.Slides](../../ishapecollection)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->