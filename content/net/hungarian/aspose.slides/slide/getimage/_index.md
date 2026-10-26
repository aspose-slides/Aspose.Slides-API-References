---
title: GetImage
second_title: Aspose.Sildes a .NET API referenciához
description: Visszaad egy Thumbnail Image objektumot egyéni méretezéssel.
type: docs
weight: 80
url: /hu/aspose.slides/slide/getimage/
---
## GetImage(float, float) {#getimage_5}

Visszaad egy Thumbnail Image objektumot egyéni méretezéssel.

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| scaleX | Single | Az érték, amellyel ezt a Thumbnail-et az x-tengely irányában méretezi. |
| scaleY | Single | Az érték, amellyel ezt a Thumbnail-et az y-tengely irányában méretezi. |

### Visszatérési érték

IImage object.

### Példák

Az alább

i példa bemutatja, hogyan lehet bélyegképeket generálni PowerPoint prezentációból.

```csharp
[C#]
// Létrehozza a Presentation osztályt, amely a prezentációs fájlt képviseli
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // Eléri az első diát
    ISlide sld = pres.Slides[0];
    // Létrehoz egy teljes méretű képet
    IImage bmp = sld.GetImage(1f, 1f);
    // Elmenti a képet a lemezre JPEG formátumban
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

Az alábbi példa bemutatja, hogyan lehet diákot bitmapre konvertálni és a képeket PNG formátumban menteni.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Átalakítja a prezentáció első diáját egy Bitmap objektummá
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // Elmenti a képet PNG formátumban
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

Az alábbi példa bemutatja, hogyan lehet PowerPoint PPT/PPTX fájlokat JPG-re konvertálni.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// Létrehoz egy teljes méretű képet
		IImage bmp = sld.GetImage(1f, 1f);
		// Elmenti a képet a lemezre JPEG formátumban
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

Az alábbi példa bemutatja, hogyan lehet PowerPoint PPT/PPTX fájlokat JPG-re konvertálni testreszabott méretekkel.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// Méretek definiálása
	int desiredX = 1200;
	int desiredY = 800;
	// Az X és Y skálázott értékeinek lekérése
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// Létrehoz egy teljes méretű képet
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// Elmenti a képet a lemezre JPEG formátumban
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### Lásd még

* interfész [IImage](../../iimage)
* osztály [Slide](../../slide)
* névtér [Aspose.Slides](../../slide)
* összeállítás [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

Visszaad egy Thumbnail Image objektumot (a valós méret 20%-a).

```csharp
public IImage GetImage()
```

### Lásd még

* interfész [IImage](../../iimage)
* osztály [Slide](../../slide)
* névtér [Aspose.Slides](../../slide)
* összeállítás [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

Visszaad egy Thumbnail Image objektumot a megadott mérettel.

```csharp
public IImage GetImage(Size imageSize)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| imageSize | Size | A létrehozandó kép mérete. |

### Visszatérési érték

Image object.

### Példák

Az alábbi példa bemutatja, hogyan lehet diákot képekké konvertálni egyéni méretekkel C#-ban.

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Átalakítja a prezentáció első diáját egy megadott méretű Bitmap objektummá
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // Elmenti a képet JPEG formátumban
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### Lásd még

* interfész [IImage](../../iimage)
* osztály [Slide](../../slide)
* névtér [Aspose.Slides](../../slide)
* összeállítás [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

Visszaad egy Thumbnail tiff image objektumot a megadott paraméterekkel.

```csharp
public IImage GetImage(ITiffOptions options)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | ITiffOptions | Tiff beállítások. |

### Visszatérési érték

Image object.

### Kivétel

| kivétel | feltétel |
| --- | --- |
| InvalidOperationException | Akkor dobódik, ha az options.SlideLayoutOption értéke NotesCommentsLayoutingOptions, és annak NotesPosition tulajdonsága a NotesPositions.BottomFull értéket veszi fel. |

### Lásd még

* interfész [IImage](../../iimage)
* interfész [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* osztály [Slide](../../slide)
* névtér [Aspose.Slides](../../slide)
* összeállítás [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

Visszaad egy Thumbnail Image objektumot.

```csharp
public IImage GetImage(IRenderingOptions options)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | IRenderingOptions | Renderelési beállítások. |

### Visszatérési érték

Image object.

### Kivétel

| kivétel | feltétel |
| --- | --- |
| InvalidOperationException | Akkor dobódik, ha a notesCommentsLayouting.NotesPosition a NotesPositions.BottomFull értéket veszi fel. |

### Lásd még

* interfész [IImage](../../iimage)
* interfész [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* osztály [Slide](../../slide)
* névtér [Aspose.Slides](../../slide)
* összeállítás [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

Visszaad egy Thumbnail Image objektumot egyéni méretezéssel.

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | IRenderingOptions | Renderelési beállítások. |
| scaleX | Single | Az érték, amellyel ezt a Thumbnail-et az x-tengely irányában méretezi. |
| scaleY | Single | Az érték, amellyel ezt a Thumbnail-et az y-tengely irányában méretezi. |

### Visszatérési érték

Bitmap objektumok.

### Kivétel

| kivétel | feltétel |
| --- | --- |
| InvalidOperationException | Akkor dobódik, ha a notesCommentsLayouting.NotesPosition a NotesPositions.BottomFull értéket veszi fel. |

### Példák

Az alábbi példa bemutatja, hogyan lehet diákot jegyzetekkel és megjegyzésekkel képekké konvertálni C#-ban.

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // Létrehozza a renderelési beállításokat
    IRenderingOptions options = new RenderingOptions();
    // Létrehozza a jegyzetek és megjegyzések elrendezési beállításait
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // Beállítja a jegyzetek pozícióját az oldalon
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // Beállítja a megjegyzések pozícióját az oldalon
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // Beállítja a megjegyzés kimeneti terület szélességét
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // Beállítja a megjegyzés terület színét
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // Beállítja a renderelés elrendezési beállításait
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // Átalakítja a prezentáció első diáját IImage objektummá
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // Elmenti a képet GIF formátumban
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### Lásd még

* interfész [IImage](../../iimage)
* interfész [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* osztály [Slide](../../slide)
* névtér [Aspose.Slides](../../slide)
* összeállítás [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

Visszaad egy Thumbnail Image objektumot a megadott mérettel.

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | IRenderingOptions | Renderelési beállítások. |
| imageSize | Size | A létrehozandó kép mérete. |

### Visszatérési érték

Image object.

### Kivétel

| kivétel | feltétel |
| --- | --- |
| InvalidOperationException | Akkor dobódik, ha az options.SlideLayoutOption értéke NotesCommentsLayoutingOptions, és annak NotesPosition tulajdonsága a NotesPositions.BottomFull értéket veszi fel. |

### Lásd még

* interfész [IImage](../../iimage)
* interfész [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* osztály [Slide](../../slide)
* névtér [Aspose.Slides](../../slide)
* összeállítás [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->