---
title: GetImage
second_title: Aspose.Sildes voor .NET API-referentie
description: Retourneert een Thumbnail Image-object met aangepaste schaal.
type: docs
weight: 80
url: /nl/aspose.slides/slide/getimage/
---
## GetImage(float, float) {#getimage_5}

Retourneert een Thumbnail Image-object met aangepaste schaal.

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scaleX | Single | De waarde waarmee deze Thumbnail in de x-asrichting wordt geschaald. |
| scaleY | Single | De waarde waarmee deze Thumbnail in de y-asrichting wordt geschaald. |

### Retourwaarde

IImage object.

### Voorbeelden

Het volgende voorbeeld laat zien hoe thumbnails van een PowerPoint Presentation te genereren.

```csharp
[C#]
// Instantieer een Presentation-klasse die het presentatie-bestand vertegenwoordigt
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // Toegang tot de eerste dia
    ISlide sld = pres.Slides[0];
    // Maak een afbeelding met volledige schaal
    IImage bmp = sld.GetImage(1f, 1f);
    // Sla de afbeelding op schijf op in JPEG-formaat
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

Het volgende voorbeeld laat zien hoe dia's naar bitmap worden geconverteerd en de afbeeldingen in PNG worden opgeslagen.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Converteert de eerste dia in de presentatie naar een Bitmap-object
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // Slaat de afbeelding op in PNG-formaat
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

Het volgende voorbeeld laat zien hoe PowerPoint PPT/PPTX naar JPG wordt geconverteerd.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// Maak een afbeelding met volledige schaal
		IImage bmp = sld.GetImage(1f, 1f);
		// Sla de afbeelding op schijf op in JPEG-formaat
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

Het volgende voorbeeld laat zien hoe PowerPoint PPT/PPTX naar JPG wordt geconverteerd met aangepaste afmetingen.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// Definieer afmetingen
	int desiredX = 1200;
	int desiredY = 800;
	// Haal geschaalde waarden van X en Y op
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// Maak een afbeelding met volledige schaal
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// Sla de afbeelding op schijf op in JPEG-formaat
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### Zie ook

* interface [IImage](../../iimage)
* klasse [Slide](../../slide)
* naamruimte [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

Retourneert een Thumbnail Image-object (20 % van de werkelijke grootte).

```csharp
public IImage GetImage()
```

### Zie ook

* interface [IImage](../../iimage)
* klasse [Slide](../../slide)
* naamruimte [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

Retourneert een Thumbnail Image-object met opgegeven grootte.

```csharp
public IImage GetImage(Size imageSize)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageSize | Size | Grootte van de afbeelding die moet worden gemaakt. |

### Retourwaarde

Image object.

### Voorbeelden

Het volgende voorbeeld laat zien hoe dia's naar afbeeldingen worden geconverteerd met aangepaste afmetingen met behulp van C#.

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Converteert de eerste dia in de presentatie naar een Bitmap met de opgegeven grootte
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // Slaat de afbeelding op in JPEG-formaat
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### Zie ook

* interface [IImage](../../iimage)
* klasse [Slide](../../slide)
* naamruimte [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

Retourneert een Thumbnail tiff-afbeeldingsobject met opgegeven parameters.

```csharp
public IImage GetImage(ITiffOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | ITiffOptions | Tiff-opties. |

### Retourwaarde

Image object.

### Uitzonderingen

| Uitzondering | Voorwaarde |
| --- | --- |
| InvalidOperationException | Wordt gegooid wanneer options.SlideLayoutOption gelijk is aan NotesCommentsLayoutingOptions en de eigenschap NotesPosition de waarde NotesPositions.BottomFull heeft. |

### Zie ook

* interface [IImage](../../iimage)
* interface [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* klasse [Slide](../../slide)
* naamruimte [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

Retourneert een Thumbnail Image-object.

```csharp
public IImage GetImage(IRenderingOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | IRenderingOptions | Rendering-opties. |

### Retourwaarde

Image object.

### Uitzonderingen

| Uitzondering | Voorwaarde |
| --- | --- |
| InvalidOperationException | Wordt gegooid wanneer notesCommentsLayouting.NotesPosition de waarde NotesPositions.BottomFull heeft. |

### Zie ook

* interface [IImage](../../iimage)
* interface [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* klasse [Slide](../../slide)
* naamruimte [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

Retourneert een Thumbnail Image-object met aangepaste schaal.

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | IRenderingOptions | Rendering-opties. |
| scaleX | Single | De waarde waarmee deze Thumbnail in de x-asrichting wordt geschaald. |
| scaleY | Single | De waarde waarmee deze Thumbnail in de y-asrichting wordt geschaald. |

### Retourwaarde

Bitmap objects.

### Uitzonderingen

| Uitzondering | Voorwaarde |
| --- | --- |
| InvalidOperationException | Wordt gegooid wanneer notesCommentsLayouting.NotesPosition de waarde NotesPositions.BottomFull heeft. |

### Voorbeelden

Het volgende voorbeeld laat zien hoe dia's met notities en opmerkingen naar afbeeldingen worden geconverteerd met behulp van C#.

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // Maak de renderingsopties
    IRenderingOptions options = new RenderingOptions();
    // Maak notities en commentaar lay-outopties
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // Stelt de positie van de notities op de pagina in
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // Stelt de positie van de opmerkingen op de pagina in
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // Stelt de breedte van het commentaar-outputgebied in
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // Stelt de kleur voor het commentaargebied in
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // Stel lay-outopties in voor het renderen
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // Converteert de eerste dia van de presentatie naar een IImage-object
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // Slaat de afbeelding op in GIF-formaat
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### Zie ook

* interface [IImage](../../iimage)
* interface [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* klasse [Slide](../../slide)
* naamruimte [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

Retourneert een Thumbnail Image-object met opgegeven grootte.

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | IRenderingOptions | Rendering-opties. |
| imageSize | Size | Grootte van de afbeelding die moet worden gemaakt. |

### Retourwaarde

Image object.

### Uitzonderingen

| Uitzondering | Voorwaarde |
| --- | --- |
| InvalidOperationException | Wordt gegooid wanneer options.SlideLayoutOption gelijk is aan NotesCommentsLayoutingOptions en de eigenschap NotesPosition de waarde NotesPositions.BottomFull heeft. |

### Zie ook

* interface [IImage](../../iimage)
* interface [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* klasse [Slide](../../slide)
* naamruimte [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->