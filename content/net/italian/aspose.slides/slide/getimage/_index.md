---
title: GetImage
second_title: Riferimento API di Aspose.Sildes per .NET
description: Restituisce un oggetto Thumbnail Image con ridimensionamento personalizzato.
type: docs
weight: 80
url: /it/aspose.slides/slide/getimage/
---
## GetImage(float, float) {#getimage_5}

Restituisce un oggetto Thumbnail Image con ridimensionamento personalizzato.

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scaleX | Single | Il valore con cui ridimensionare questo Thumbnail nell'asse x. |
| scaleY | Single | Il valore con cui ridimensionare questo Thumbnail nell'asse y. |

### Valore restituito

oggetto IImage.

### Esempi

Il seguente esempio mostra come generare miniature da una presentazione PowerPoint.

```csharp
[C#]
// Istanziare una classe Presentation che rappresenta il file della presentazione
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // Accedere alla prima diapositiva
    ISlide sld = pres.Slides[0];
    // Creare un'immagine a scala intera
    IImage bmp = sld.GetImage(1f, 1f);
    // Salvare l'immagine su disco in formato JPEG
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

Il seguente esempio mostra come convertire le diapositive in bitmap e salvare le immagini in PNG.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Converte la prima diapositiva nella presentazione in un oggetto Bitmap
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // Salva l'immagine nel formato PNG
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

Il seguente esempio mostra come convertire PowerPoint PPT/PPTX in JPG.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// Crea un'immagine a scala intera
		IImage bmp = sld.GetImage(1f, 1f);
		// Salva l'immagine su disco in formato JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

Il seguente esempio mostra come convertire PowerPoint PPT/PPTX in JPG con dimensioni personalizzate.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// Definisci le dimensioni
	int desiredX = 1200;
	int desiredY = 800;
	// Ottieni i valori scalati di X e Y
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// Crea un'immagine a scala intera
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// Salva l'immagine su disco in formato JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### Vedi anche

* interfaccia [IImage](../../iimage)
* classe [Slide](../../slide)
* spazio dei nomi [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

Restituisce un oggetto Thumbnail Image (20% della dimensione reale).

```csharp
public IImage GetImage()
```

### Vedi anche

* interfaccia [IImage](../../iimage)
* classe [Slide](../../slide)
* spazio dei nomi [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

Restituisce un oggetto Thumbnail Image con dimensione specificata.

```csharp
public IImage GetImage(Size imageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageSize | Size | Dimensione dell'immagine da creare. |

### Valore restituito

oggetto Image.

### Esempi

Il seguente esempio mostra come convertire le diapositive in immagini con dimensioni personalizzate utilizzando C#.

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Converte la prima diapositiva nella presentazione in un Bitmap con la dimensione specificata
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // Salva l'immagine nel formato JPEG
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### Vedi anche

* interfaccia [IImage](../../iimage)
* classe [Slide](../../slide)
* spazio dei nomi [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

Restituisce un oggetto Thumbnail tiff image con parametri specificati.

```csharp
public IImage GetImage(ITiffOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | ITiffOptions | Opzioni Tiff. |

### Valore restituito

oggetto Image.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| InvalidOperationException | Generata quando options.SlideLayoutOption è NotesCommentsLayoutingOptions e la sua proprietà NotesPosition assume il valore NotesPositions.BottomFull. |

### Vedi anche

* interfaccia [IImage](../../iimage)
* interfaccia [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* classe [Slide](../../slide)
* spazio dei nomi [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

Restituisce un oggetto Thumbnail Image.

```csharp
public IImage GetImage(IRenderingOptions options)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | IRenderingOptions | Opzioni di rendering. |

### Valore restituito

oggetto Image.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| InvalidOperationException | Generata quando notesCommentsLayouting.NotesPosition assume il valore NotesPositions.BottomFull |

### Vedi anche

* interfaccia [IImage](../../iimage)
* interfaccia [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* classe [Slide](../../slide)
* spazio dei nomi [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

Restituisce un oggetto Thumbnail Image con ridimensionamento personalizzato.

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | IRenderingOptions | Opzioni di rendering. |
| scaleX | Single | Il valore con cui ridimensionare questo Thumbnail nell'asse x. |
| scaleY | Single | Il valore con cui ridimensionare questo Thumbnail nell'asse y. |

### Valore restituito

oggetti Bitmap.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| InvalidOperationException | Generata quando notesCommentsLayouting.NotesPosition assume il valore NotesPositions.BottomFull |

### Esempi

Il seguente esempio mostra come convertire le diapositive con note e commenti in immagini utilizzando C#.

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // Crea le opzioni di rendering
    IRenderingOptions options = new RenderingOptions();
    // Crea le opzioni di layout per note e commenti
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // Imposta la posizione delle note sulla pagina
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // Imposta la posizione dei commenti sulla pagina
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // Imposta la larghezza dell'area di output dei commenti
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // Imposta il colore dell'area dei commenti
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // Imposta le opzioni di layout per il rendering
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // Converte la prima diapositiva della presentazione in un oggetto IImage
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // Salva l'immagine nel formato GIF
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### Vedi anche

* interfaccia [IImage](../../iimage)
* interfaccia [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* classe [Slide](../../slide)
* spazio dei nomi [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

Restituisce un oggetto Thumbnail Image con dimensione specificata.

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | IRenderingOptions | Opzioni di rendering. |
| imageSize | Size | Dimensione dell'immagine da creare. |

### Valore restituito

oggetto Image.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| InvalidOperationException | Generata quando options.SlideLayoutOption è NotesCommentsLayoutingOptions e la sua proprietà NotesPosition assume il valore NotesPositions.BottomFull. |

### Vedi anche

* interfaccia [IImage](../../iimage)
* interfaccia [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* classe [Slide](../../slide)
* spazio dei nomi [Aspose.Slides](../../slide)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->