---
title: Slide
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una diapositiva in una presentazione.
type: docs
url: /it/com.aspose.slides/slide/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Tutte le interfacce implementate:**
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)
```
public final class Slide extends BaseSlide implements ISlide
```

Rappresenta una diapositiva in una presentazione.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Restituisce il gestore HeaderFooter della diapositiva. |
| [getThemeManager()](#getThemeManager--) | Restituisce il gestore del tema di sovrascrittura. |
| [getSlideNumber()](#getSlideNumber--) | Restituisce il numero della diapositiva. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Restituisce il numero della diapositiva. |
| [getHidden()](#getHidden--) | Determina se la diapositiva specificata è nascosta durante una presentazione. |
| [setHidden(boolean value)](#setHidden-boolean-) | Determina se la diapositiva specificata è nascosta durante una presentazione. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specifica se le forme sulla diapositiva master devono essere mostrate nelle diapositive o meno. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specifica se le forme sulla diapositiva master devono essere mostrate nelle diapositive o meno. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Restituisce un oggetto Thumbnail Image con scala personalizzata. |
| [getImage()](#getImage--) | Restituisce un oggetto Thumbnail Image (20% della dimensione reale). |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Restituisce un oggetto Thumbnail Image con dimensione specificata. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Restituisce un oggetto immagine tiff Thumbnail con parametri specificati. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Restituisce un oggetto Thumbnail Image. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Restituisce un oggetto Thumbnail Image con scala personalizzata. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Restituisce un oggetto Thumbnail Image con dimensione specificata. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Salva il contenuto della diapositiva come file SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Salva il contenuto della diapositiva come file SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Salva il contenuto della diapositiva come file EMF. |
| [remove()](#remove--) | Rimuove la diapositiva dalla presentazione. |
| [getLayoutSlide()](#getLayoutSlide--) | Restituisce o imposta la diapositiva layout per la diapositiva corrente. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Restituisce o imposta la diapositiva layout per la diapositiva corrente. |
| [reset()](#reset--) | Resetta posizione, dimensione e formattazione di ogni forma che ha un prototipo su LayoutSlide. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Consente di accedere alla diapositiva note, aggiungerla e rimuoverla. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Restituisce tutti i commenti della diapositiva aggiunti da un autore specifico. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Unisce i run con la stessa formattazione in tutti i paragrafi in tutte le forme accettabili. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

Restituisce il gestore HeaderFooter della diapositiva. Solo lettura [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Restituisce:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Restituisce il gestore del tema di sovrascrittura. Solo lettura [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Restituisce:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

Restituisce il numero della diapositiva. L'indice della diapositiva nella collezione [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) è sempre uguale a SlideNumber - Presentation.FirstSlideNumber. Lettura/Scrittura int.

**Restituisce:**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

Imposta il numero della diapositiva. L'indice della diapositiva nella collezione [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) è sempre uguale a SlideNumber - Presentation.FirstSlideNumber. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Determina se la diapositiva specificata è nascosta durante una presentazione. Lettura/Scrittura boolean.

**Restituisce:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Determina se la diapositiva specificata è nascosta durante una presentazione. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Specifica se le forme sulla diapositiva master devono essere mostrate nelle diapositive o meno. Lettura/Scrittura boolean.

**Restituisce:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Specifica se le forme sulla diapositiva master devono essere mostrate nelle diapositive o meno. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

Restituisce un oggetto Thumbnail Image con scala personalizzata.

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // Accedi alla prima diapositiva
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Crea un'immagine a scala completa
>      IImage bmp = sld.getImage(1f, 1f);
>      // Salva l'immagine su disco in formato JPEG
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Converte la prima diapositiva della presentazione in un oggetto Bitmap
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // Salva l'immagine nel formato PNG
>      bmp.save("Slide_0.png", ImageFormat.Png);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.ppt");
>  try {
>      for (ISlide sld : pres.getSlides())
>      {
>          // Crea un'immagine a scala completa
>          IImage bmp = sld.getImage(1f, 1f);
>          // Salva l'immagine su disco in formato JPEG
>          bmp.save("Slide_"+sld.getSlideNumber()+"0.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG with customized dimensions.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.pptx");
>  try {
>      // Definisci le dimensioni
>      int desiredX = 1200;
>      int desiredY = 800;
>      // Ottieni i valori scalati di X e Y
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // Crea un'immagine a scala completa
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // Salva l'immagine su disco in formato JPEG
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scaleX | float | Il valore con cui scalare questo Thumbnail nella direzione dell'asse x. |
| scaleY | float | Il valore con cui scalare questo Thumbnail nella direzione dell'asse y. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - IImage object.

### getImage() {#getImage--}
```
public final IImage getImage()
```

Restituisce un oggetto Thumbnail Image (20% della dimensione reale).

**Restituisce:**
[IImage](../../com.aspose.slides/iimage)

### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public final IImage getImage(Size imageSize)
```

Restituisce un oggetto Thumbnail Image con dimensione specificata.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Converte la prima diapositiva della presentazione in un Bitmap con le dimensioni specificate
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new com.aspose.slides.android.Size(1820, 1040));
>      // Salva l'immagine nel formato JPEG
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Dimensione dell'immagine da creare. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

Restituisce un oggetto immagine tiff Thumbnail con parametri specificati.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Opzioni tiff. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

Restituisce un oggetto Thumbnail Image.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni di rendering. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Restituisce un oggetto Thumbnail Image con scala personalizzata.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // Crea le opzioni di rendering
>      IRenderingOptions options = new RenderingOptions();
>      // Crea le opzioni di layout per note e commenti
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // Imposta la posizione delle note sulla pagina
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // Imposta la posizione dei commenti sulla pagina
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // Imposta la larghezza dell'area di output dei commenti
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // Imposta il colore per l'area dei commenti
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // Imposta le opzioni di layout per il rendering
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // Converte la prima diapositiva della presentazione in un oggetto android.graphics.Bitmap
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // Salva l'immagine nel formato GIF
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni di rendering. |
| scaleX | float | Il valore con cui scalare questo Thumbnail nella direzione dell'asse x. |
| scaleY | float | Il valore con cui scalare questo Thumbnail nella direzione dell'asse y. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage getImage(IRenderingOptions options, Size imageSize)
```

Restituisce un oggetto Thumbnail Image con dimensione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni di rendering. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Dimensione dell'immagine da creare. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Image object.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Salva il contenuto della diapositiva come file SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // Salva la prima diapositiva come file SVG
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream di destinazione |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Salva il contenuto della diapositiva come file SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // Salva la prima diapositiva come file SVG
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream di destinazione |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opzioni di generazione SVG |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Salva il contenuto della diapositiva come file EMF.

--------------------

> ```
> Il seguente esempio di codice dimostra come convertire la prima diapositiva da una presentazione PowerPoint in un metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // Salva la prima diapositiva come metafile
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream di destinazione |

### remove() {#remove--}
```
public final void remove()
```

Rimuove la diapositiva dalla presentazione.

### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

Restituisce o imposta la diapositiva layout per la diapositiva corrente. Lettura/Scrittura [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

Restituisce o imposta la diapositiva layout per la diapositiva corrente. Lettura/Scrittura [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### reset() {#reset--}
```
public final void reset()
```

Resetta posizione, dimensione e formattazione di ogni forma che ha un prototipo su LayoutSlide.

### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

Consente di accedere alla diapositiva note, aggiungerla e rimuoverla. Solo lettura [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Restituisce:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

Restituisce tutti i commenti della diapositiva aggiunti da un autore specifico.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Autore dei commenti da trovare o null per restituire tutti i commenti. |

**Restituisce:**
com.aspose.slides.IComment[] - Array di [Comment](../../com.aspose.slides/comment).

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Unisce i run con la stessa formattazione in tutti i paragrafi in tutte le forme accettabili.