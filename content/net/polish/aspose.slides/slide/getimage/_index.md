---
title: GetImage
second_title: Aspose.Sildes dla .NET – odniesienie API
description: Zwraca obiekt Thumbnail Image z niestandardowym skalowaniem.
type: docs
weight: 80
url: /pl/aspose.slides/slide/getimage/
---
## GetImage(float, float) {#getimage_5}

Zwraca obiekt Thumbnail Image z niestandardowym skalowaniem.

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| scaleX | Single | Wartość, o którą należy skalować tę miniaturę wzdłuż osi x. |
| scaleY | Single | Wartość, o którą należy skalować tę miniaturę wzdłuż osi y. |

### Wartość zwracana

Obiekt IImage.

### Przykłady

Poniższy przykład pokazuje, jak generować miniatury z prezentacji PowerPoint.

```csharp
[C#]
// Utwórz instancję klasy Presentation, która reprezentuje plik prezentacji
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // Uzyskaj dostęp do pierwszego slajdu
    ISlide sld = pres.Slides[0];
    // Utwórz obraz w pełnej skali
    IImage bmp = sld.GetImage(1f, 1f);
    // Zapisz obraz na dysku w formacie JPEG
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

Poniższy przykład pokazuje, jak konwertować slajdy na bitmapy i zapisywać obrazy w formacie PNG.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Konwertuje pierwszy slajd w prezentacji na obiekt Bitmap
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // Zapisuje obraz w formacie PNG
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

Poniższy przykład pokazuje, jak konwertować pliki PowerPoint PPT/PPTX na JPG.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// Utwórz obraz w pełnej skali
		IImage bmp = sld.GetImage(1f, 1f);
		// Zapisz obraz na dysku w formacie JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

Poniższy przykład pokazuje, jak konwertować pliki PowerPoint PPT/PPTX na JPG z niestandardowymi wymiarami.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// Zdefiniuj wymiary
	int desiredX = 1200;
	int desiredY = 800;
	// Pobierz przeskalowane wartości X i Y
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// Utwórz obraz w pełnej skali
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// Zapisz obraz na dysku w formacie JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### Zobacz także

* interfejs [IImage](../../iimage)
* klasa [Slide](../../slide)
* przestrzeń nazw [Aspose.Slides](../../slide)
* zestaw [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

Zwraca obiekt Thumbnail Image (20 % rzeczywistego rozmiaru).

```csharp
public IImage GetImage()
```

### Zobacz także

* interfejs [IImage](../../iimage)
* klasa [Slide](../../slide)
* przestrzeń nazw [Aspose.Slides](../../slide)
* zestaw [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

Zwraca obiekt Thumbnail Image o określonym rozmiarze.

```csharp
public IImage GetImage(Size imageSize)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| imageSize | Size | Rozmiar obrazu do utworzenia. |

### Wartość zwracana

Obiekt Image.

### Przykłady

Poniższy przykład pokazuje, jak konwertować slajdy na obrazy o niestandardowych rozmiarach przy użyciu C#.

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Konwertuje pierwszy slajd w prezentacji na obiekt Bitmap o określonym rozmiarze
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // Zapisuje obraz w formacie JPEG
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### Zobacz także

* interfejs [IImage](../../iimage)
* klasa [Slide](../../slide)
* przestrzeń nazw [Aspose.Slides](../../slide)
* zestaw [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

Zwraca obiekt miniatury obrazu tiff z określonymi parametrami.

```csharp
public IImage GetImage(ITiffOptions options)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | ITiffOptions | Opcje Tiff. |

### Wartość zwracana

Obiekt Image.

### Wyjątki

| wyjątek | warunek |
| --- | --- |
| InvalidOperationException | Rzucany, gdy options.SlideLayoutOption jest NotesCommentsLayoutingOptions i jego właściwość NotesPosition ma wartość NotesPositions.BottomFull. |

### Zobacz także

* interfejs [IImage](../../iimage)
* interfejs [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* klasa [Slide](../../slide)
* przestrzeń nazw [Aspose.Slides](../../slide)
* zestaw [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

Zwraca obiekt Thumbnail Image.

```csharp
public IImage GetImage(IRenderingOptions options)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | IRenderingOptions | Opcje renderowania. |

### Wartość zwracana

Obiekt Image.

### Wyjątki

| wyjątek | warunek |
| --- | --- |
| InvalidOperationException | Rzucany, gdy notesCommentsLayouting.NotesPosition przyjmuje wartość NotesPositions.BottomFull |

### Zobacz także

* interfejs [IImage](../../iimage)
* interfejs [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* klasa [Slide](../../slide)
* przestrzeń nazw [Aspose.Slides](../../slide)
* zestaw [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

Zwraca obiekt Thumbnail Image z niestandardowym skalowaniem.

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | IRenderingOptions | Opcje renderowania. |
| scaleX | Single | Wartość, o którą należy skalować tę miniaturę wzdłuż osi x. |
| scaleY | Single | Wartość, o którą należy skalować tę miniaturę wzdłuż osi y. |

### Wartość zwracana

Obiekty Bitmap.

### Wyjątki

| wyjątek | warunek |
| --- | --- |
| InvalidOperationException | Rzucany, gdy notesCommentsLayouting.NotesPosition przyjmuje wartość NotesPositions.BottomFull |

### Przykłady

Poniższy przykład pokazuje, jak konwertować slajdy z notatkami i komentarzami na obrazy przy użyciu C#.

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // Utwórz opcje renderowania
    IRenderingOptions options = new RenderingOptions();
    // Utwórz opcje układu notatek i komentarzy
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // Ustawia pozycję notatek na stronie
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // Ustawia pozycję komentarzy na stronie
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // Ustawia szerokość obszaru komentarzy
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // Ustawia kolor obszaru komentarzy
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // Ustaw opcje układu dla renderowania
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // Konwertuje pierwszy slajd prezentacji na obiekt IImage
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // Zapisuje obraz w formacie GIF
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### Zobacz także

* interfejs [IImage](../../iimage)
* interfejs [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* klasa [Slide](../../slide)
* przestrzeń nazw [Aspose.Slides](../../slide)
* zestaw [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

Zwraca obiekt Thumbnail Image o określonym rozmiarze.

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| options | IRenderingOptions | Opcje renderowania. |
| imageSize | Size | Rozmiar obrazu do utworzenia. |

### Wartość zwracana

Obiekt Image.

### Wyjątki

| wyjątek | warunek |
| --- | --- |
| InvalidOperationException | Rzucany, gdy options.SlideLayoutOption jest NotesCommentsLayoutingOptions i jego właściwość NotesPosition ma wartość NotesPositions.BottomFull. |

### Zobacz także

* interfejs [IImage](../../iimage)
* interfejs [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* klasa [Slide](../../slide)
* przestrzeń nazw [Aspose.Slides](../../slide)
* zestaw [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->