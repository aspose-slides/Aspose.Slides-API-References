---
title: GetImage
second_title: Aspose.Sildes för .NET API-referens
description: Returnerar ett Thumbnail Image-objekt med anpassad skalning.
type: docs
weight: 80
url: /sv/aspose.slides/slide/getimage/
---
## GetImage(float, float) {#getimage_5}

Returnerar ett Thumbnail Image-objekt med anpassad skalning.

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scaleX | Single | Värdet som används för att skala denna Thumbnail i x-axelns riktning. |
| scaleY | Single | Värdet som används för att skala denna Thumbnail i y-axelns riktning. |

### Returvärde

IImage-objekt.

### Exempel

Följande exempel visar hur man genererar miniatyrbilder från en PowerPoint-presentation.

```csharp
[C#]
// Instansiera en Presentation-klass som representerar presentationsfilen
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // Hämta den första bilden
    ISlide sld = pres.Slides[0];
    // Skapa en fullskalig bild
    IImage bmp = sld.GetImage(1f, 1f);
    // Spara bilden till disk i JPEG-format
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

Följande exempel visar hur man konverterar bilder till bitmap och sparar bilderna i PNG.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Konverterar den första bilden i presentationen till ett Bitmap-objekt
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // Sparar bilden i PNG-format
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

Följande exempel visar hur man konverterar PowerPoint PPT/PPTX till JPG.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// Skapa en fullskalig bild
		IImage bmp = sld.GetImage(1f, 1f);
		// Spara bilden till disk i JPEG-format
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

Följande exempel visar hur man konverterar PowerPoint PPT/PPTX till JPG med anpassade dimensioner.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// Definiera dimensioner
	int desiredX = 1200;
	int desiredY = 800;
	// Hämta skalade värden för X och Y
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// Skapa en fullskalig bild
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// Spara bilden till disk i JPEG-format
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### Se också

* gränssnitt [IImage](../../iimage)
* klass [Slide](../../slide)
* namnrymd [Aspose.Slides](../../slide)
* samling [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

Returnerar ett Thumbnail Image-objekt (20% av verklig storlek).

```csharp
public IImage GetImage()
```

### Se också

* gränssnitt [IImage](../../iimage)
* klass [Slide](../../slide)
* namnrymd [Aspose.Slides](../../slide)
* samling [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

Returnerar ett Thumbnail Image-objekt med angiven storlek.

```csharp
public IImage GetImage(Size imageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageSize | Size | Storlek på bilden som ska skapas. |

### Returvärde

Image-objekt.

### Exempel

Följande exempel visar hur man konverterar bilder till bilder med anpassade storlekar med C#.

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Konverterar den första bilden i presentationen till en Bitmap med angiven storlek
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // Sparar bilden i JPEG-format
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### Se också

* gränssnitt [IImage](../../iimage)
* klass [Slide](../../slide)
* namnrymd [Aspose.Slides](../../slide)
* samling [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

Returnerar ett Thumbnail tiff-bildobjekt med angivna parametrar.

```csharp
public IImage GetImage(ITiffOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | ITiffOptions | Tiff-alternativ. |

### Returvärde

Image-objekt.

### Undantag

| undantag | villkor |
| --- | --- |
| InvalidOperationException | Kastas när options.SlideLayoutOption är NotesCommentsLayoutingOptions och dess egenskap NotesPosition har värdet NotesPositions.BottomFull. |

### Se också

* gränssnitt [IImage](../../iimage)
* gränssnitt [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* klass [Slide](../../slide)
* namnrymd [Aspose.Slides](../../slide)
* samling [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

Returnerar ett Thumbnail Image-objekt.

```csharp
public IImage GetImage(IRenderingOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | IRenderingOptions | Renderingsalternativ. |

### Returvärde

Image-objekt.

### Undantag

| undantag | villkor |
| --- | --- |
| InvalidOperationException | Kastas när notesCommentsLayouting.NotesPosition har värdet NotesPositions.BottomFull |

### Se också

* gränssnitt [IImage](../../iimage)
* gränssnitt [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* klass [Slide](../../slide)
* namnrymd [Aspose.Slides](../../slide)
* samling [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

Returnerar ett Thumbnail Image-objekt med anpassad skalning.

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | IRenderingOptions | Renderingsalternativ. |
| scaleX | Single | Värdet som används för att skala denna Thumbnail i x-axelns riktning. |
| scaleY | Single | Värdet som används för att skala denna Thumbnail i y-axelns riktning. |

### Returvärde

Bitmap-objekt.

### Undantag

| undantag | villkor |
| --- | --- |
| InvalidOperationException | Kastas när notesCommentsLayouting.NotesPosition har värdet NotesPositions.BottomFull |

### Exempel

Följande exempel visar hur man konverterar bilder med anteckningar och kommentarer till bilder med C#.

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // Skapa renderingsalternativen
    IRenderingOptions options = new RenderingOptions();
    // Skapa layoutalternativ för anteckningar och kommentarer
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // Anger positionen för anteckningarna på sidan
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // Anger positionen för kommentarerna på sidan
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // Anger bredden på kommentarsutmatningsområdet
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // Anger färgen för kommentarsområdet
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // Ställ in layoutalternativ för rendering
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // Konverterar den första bilden i presentationen till ett IImage-objekt
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // Sparar bilden i GIF-format
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### Se också

* gränssnitt [IImage](../../iimage)
* gränssnitt [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* klass [Slide](../../slide)
* namnrymd [Aspose.Slides](../../slide)
* samling [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

Returnerar ett Thumbnail Image-objekt med angiven storlek.

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | IRenderingOptions | Renderingsalternativ. |
| imageSize | Size | Storlek på bilden som ska skapas. |

### Returvärde

Image-objekt.

### Undantag

| undantag | villkor |
| --- | --- |
| InvalidOperationException | Kastas när options.SlideLayoutOption är NotesCommentsLayoutingOptions och dess egenskap NotesPosition har värdet NotesPositions.BottomFull. |

### Se också

* gränssnitt [IImage](../../iimage)
* gränssnitt [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* klass [Slide](../../slide)
* namnrymd [Aspose.Slides](../../slide)
* samling [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->