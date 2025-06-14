---
title: GetImage
second_title: Aspose.Sildes für .NET API-Referenz
description: Gibt ein Thumbnail-Image-Objekt mit benutzerdefinierter Skalierung zurück.
type: docs
weight: 80
url: /de/aspose.slides/slide/getimage/
---

## GetImage(float, float) {#getimage_5}

Gibt ein Thumbnail-Image-Objekt mit benutzerdefinierter Skalierung zurück.

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scaleX | Single | Der Wert, um den dieses Thumbnail in x-Achsen-Richtung skaliert werden soll. |
| scaleY | Single | Der Wert, um den dieses Thumbnail in y-Achsen-Richtung skaliert werden soll. |

### Rückgabewert

IImage-Objekt.

### Beispiele

Das folgende Beispiel zeigt, wie man Thumbnails aus einer PowerPoint-Präsentation erzeugt.

```csharp
[C#]
// Instanziiere eine Präsentationsklasse, die die Präsentationsdatei darstellt
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // Greife auf die erste Folie zu
    ISlide sld = pres.Slides[0];
    // Erstelle ein Bild in voller Größe
    IImage bmp = sld.GetImage(1f, 1f);
    // Speichere das Bild auf der Festplatte im JPEG-Format
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

Das folgende Beispiel zeigt, wie man Folien in Bitmap konvertiert und die Bilder im PNG-Format speichert.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Konvertiert die erste Folie in der Präsentation in ein Bitmap-Objekt
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // Speichert das Bild im PNG-Format
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

Das folgende Beispiel zeigt, wie man PowerPoint PPT/PPTX in JPG konvertiert.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// Erstelle ein Bild in voller Größe
		IImage bmp = sld.GetImage(1f, 1f);
		// Speichere das Bild auf der Festplatte im JPEG-Format
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

Das folgende Beispiel zeigt, wie man PowerPoint PPT/PPTX in JPG mit benutzerdefinierten Abmessungen konvertiert.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// Definiere Abmessungen
	int desiredX = 1200;
	int desiredY = 800;
	// Erhalte skalierte Werte von X und Y
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// Erstelle ein Bild in voller Größe
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// Speichere das Bild auf der Festplatte im JPEG-Format
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### Siehe auch

* Schnittstelle [IImage](../../iimage)
* Klasse [Slide](../../slide)
* Namespace [Aspose.Slides](../../slide)
* Assembly [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

Gibt ein Thumbnail-Image-Objekt (20% der echten Größe) zurück.

```csharp
public IImage GetImage()
```

### Siehe auch

* Schnittstelle [IImage](../../iimage)
* Klasse [Slide](../../slide)
* Namespace [Aspose.Slides](../../slide)
* Assembly [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

Gibt ein Thumbnail-Image-Objekt mit einer bestimmten Größe zurück.

```csharp
public IImage GetImage(Size imageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageSize | Size | Größe des zu erstellenden Bildes. |

### Rückgabewert

Image-Objekt.

### Beispiele

Das folgende Beispiel zeigt, wie man Folien in Bilder mit benutzerdefinierten Größen konvertiert.

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Konvertiert die erste Folie in der Präsentation in ein Bitmap mit der angegebenen Größe
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // Speichert das Bild im JPEG-Format
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### Siehe auch

* Schnittstelle [IImage](../../iimage)
* Klasse [Slide](../../slide)
* Namespace [Aspose.Slides](../../slide)
* Assembly [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

Gibt ein Thumbnail-TIFF-Image-Objekt mit bestimmten Parametern zurück.

```csharp
public IImage GetImage(ITiffOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | ITiffOptions | TIFF-Optionen. |

### Rückgabewert

Image-Objekt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| InvalidOperationException | Wird ausgelöst, wenn options.SlideLayoutOption NotesCommentsLayoutingOptions ist und die Eigenschaft NotesPosition den Wert NotesPositions.BottomFull annimmt. |

### Siehe auch

* Schnittstelle [IImage](../../iimage)
* Schnittstelle [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* Klasse [Slide](../../slide)
* Namespace [Aspose.Slides](../../slide)
* Assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

Gibt ein Thumbnail-Image-Objekt zurück.

```csharp
public IImage GetImage(IRenderingOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | IRenderingOptions | Rendering-Optionen. |

### Rückgabewert

Image-Objekt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| InvalidOperationException | Wird ausgelöst, wenn notesCommentsLayouting.NotesPosition den Wert NotesPositions.BottomFull annimmt. |

### Siehe auch

* Schnittstelle [IImage](../../iimage)
* Schnittstelle [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* Klasse [Slide](../../slide)
* Namespace [Aspose.Slides](../../slide)
* Assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

Gibt ein Thumbnail-Image-Objekt mit benutzerdefinierter Skalierung zurück.

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | IRenderingOptions | Rendering-Optionen. |
| scaleX | Single | Der Wert, um den dieses Thumbnail in x-Achsen-Richtung skaliert werden soll. |
| scaleY | Single | Der Wert, um den dieses Thumbnail in y-Achsen-Richtung skaliert werden soll. |

### Rückgabewert

Bitmap-Objekte.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| InvalidOperationException | Wird ausgelöst, wenn notesCommentsLayouting.NotesPosition den Wert NotesPositions.BottomFull annimmt. |

### Beispiele

Das folgende Beispiel zeigt, wie man Folien mit Notizen und Kommentaren in Bilder konvertiert.

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // Erstelle die Rendering-Optionen
    IRenderingOptions options = new RenderingOptions();
    // Erstelle Notizen- und Kommentaranordnung
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // Setzt die Position der Notizen auf der Seite
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // Setzt die Position der Kommentare auf der Seite
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // Setzt die Breite des Kommentar-Ausgabebereichs
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // Setzt die Farbe für den Kommentarbereich
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // Setzt Layout-Optionen für das Rendering
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // Konvertiert die erste Folie der Präsentation in ein IImage-Objekt
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // Speichert das Bild im GIF-Format
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### Siehe auch

* Schnittstelle [IImage](../../iimage)
* Schnittstelle [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* Klasse [Slide](../../slide)
* Namespace [Aspose.Slides](../../slide)
* Assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

Gibt ein Thumbnail-Image-Objekt mit einer bestimmten Größe zurück.

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | IRenderingOptions | Rendering-Optionen. |
| imageSize | Size | Größe des zu erstellenden Bildes. |

### Rückgabewert

Image-Objekt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| InvalidOperationException | Wird ausgelöst, wenn options.SlideLayoutOption NotesCommentsLayoutingOptions ist und die Eigenschaft NotesPosition den Wert NotesPositions.BottomFull annimmt. |

### Siehe auch

* Schnittstelle [IImage](../../iimage)
* Schnittstelle [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* Klasse [Slide](../../slide)
* Namespace [Aspose.Slides](../../slide)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->