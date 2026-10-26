---
title: GetImage
second_title: Aspose.Slides pro .NET API Reference
description: Vrací objekt Thumbnail Image s vlastním měřítkem.
type: docs
weight: 80
url: /cs/aspose.slides/slide/getimage/
---
## GetImage(float, float) {#getimage_5}

Vrací objekt Thumbnail Image se vlastním měřítkem.

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| scaleX | Single | Hodnota, o kterou se má tato miniatura zvětšit ve směru osy x. |
| scaleY | Single | Hodnota, o kterou se má tato miniatura zvětšit ve směru osy y. |

### Návratová hodnota

Objekt IImage.

### Příklady

Následující příklad ukazuje, jak generovat miniatury z PowerPoint prezentace.

```csharp
[C#]
// Vytvořte instanci třídy Presentation, která představuje soubor prezentace
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // Přístup k prvnímu snímku
    ISlide sld = pres.Slides[0];
    // Vytvořte obrázek v plném měřítku
    IImage bmp = sld.GetImage(1f, 1f);
    // Uložte obrázek na disk ve formátu JPEG
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

Následující příklad ukazuje, jak převádět snímky na bitmapu a ukládat obrázky ve formátu PNG.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Převádí první snímek v prezentaci na objekt Bitmap
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // Ukládá obrázek ve formátu PNG
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

Následující příklad ukazuje, jak převést PowerPoint PPT/PPTX na JPG.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// Vytvořte obrázek v plném měřítku
		IImage bmp = sld.GetImage(1f, 1f);
		// Uložte obrázek na disk ve formátu JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

Následující příklad ukazuje, jak převést PowerPoint PPT/PPTX na JPG s vlastním rozměrem.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// Definujte rozměry
	int desiredX = 1200;
	int desiredY = 800;
	// Získejte škálované hodnoty X a Y
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// Vytvořte obrázek v plném měřítku
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// Uložte obrázek na disk ve formátu JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### Viz také

* interface [IImage](../../iimage)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

Vrací objekt Thumbnail Image (20 % skutečné velikosti).

```csharp
public IImage GetImage()
```

### Viz také

* interface [IImage](../../iimage)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

Vrací objekt Thumbnail Image s určenou velikostí.

```csharp
public IImage GetImage(Size imageSize)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| imageSize | Size | Velikost obrázku, který se má vytvořit. |

### Návratová hodnota

Objekt Image.

### Příklady

Následující příklad ukazuje, jak převádět snímky na obrázky s vlastními rozměry pomocí C#.

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Převede první snímek v prezentaci na bitmapu se zadanou velikostí
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // Uloží obrázek ve formátu JPEG
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### Viz také

* interface [IImage](../../iimage)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

Vrací objekt Thumbnail tiff image s určenými parametry.

```csharp
public IImage GetImage(ITiffOptions options)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | ITiffOptions | Možnosti tiff. |

### Návratová hodnota

Objekt Image.

### Výjimky

| Výjimka | Podmínka |
| --- | --- |
| InvalidOperationException | Vyvolána, když options.SlideLayoutOption je NotesCommentsLayoutingOptions a jeho vlastnost NotesPosition má hodnotu NotesPositions.BottomFull. |

### Viz také

* interface [IImage](../../iimage)
* interface [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

Vrací objekt Thumbnail Image.

```csharp
public IImage GetImage(IRenderingOptions options)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | IRenderingOptions | Možnosti vykreslování. |

### Návratová hodnota

Objekt Image.

### Výjimky

| Výjimka | Podmínka |
| --- | --- |
| InvalidOperationException | Vyvolána, když notesCommentsLayouting.NotesPosition má hodnotu NotesPositions.BottomFull. |

### Viz také

* interface [IImage](../../iimage)
* interface [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

Vrací objekt Thumbnail Image se vlastním měřítkem.

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | IRenderingOptions | Možnosti vykreslování. |
| scaleX | Single | Hodnota, o kterou se má tato miniatura zvětšit ve směru osy x. |
| scaleY | Single | Hodnota, o kterou se má tato miniatura zvětšit ve směru osy y. |

### Návratová hodnota

Objekty Bitmap.

### Výjimky

| Výjimka | Podmínka |
| --- | --- |
| InvalidOperationException | Vyvolána, když notesCommentsLayouting.NotesPosition má hodnotu NotesPositions.BottomFull. |

### Příklady

Následující příklad ukazuje, jak převádět snímky s poznámkami a komentáři na obrázky pomocí C#.

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // Vytvořte možnosti vykreslování
    IRenderingOptions options = new RenderingOptions();
    // Vytvořte možnosti rozložení poznámek a komentářů
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // Nastaví pozici poznámek na stránce
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // Nastaví pozici komentářů na stránce
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // Nastaví šířku výstupní oblasti komentářů
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // Nastaví barvu oblasti komentářů
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // Nastavte možnosti rozložení pro vykreslování
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // Převede první snímek prezentace na objekt IImage
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // Uloží obrázek ve formátu GIF
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### Viz také

* interface [IImage](../../iimage)
* interface [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

Vrací objekt Thumbnail Image s určenou velikostí.

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| options | IRenderingOptions | Možnosti vykreslování. |
| imageSize | Size | Velikost obrázku, který se má vytvořit. |

### Návratová hodnota

Objekt Image.

### Výjimky

| Výjimka | Podmínka |
| --- | --- |
| InvalidOperationException | Vyvolána, když options.SlideLayoutOption je NotesCommentsLayoutingOptions a jeho vlastnost NotesPosition má hodnotu NotesPositions.BottomFull. |

### Viz také

* interface [IImage](../../iimage)
* interface [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* class [Slide](../../slide)
* namespace [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->