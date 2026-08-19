---
title: ISlide
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una diapositiva in una presentazione.
type: docs
url: /it/com.aspose.slides/islide/
---
**Tutte le Interfacce Implementate:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

Rappresenta una diapositiva in una presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Restituisce il gestore HeaderFooter della diapositiva. |
| [getSlideNumber()](#getSlideNumber--) | Restituisce il numero della diapositiva. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Restituisce il numero della diapositiva. |
| [getHidden()](#getHidden--) | Determina se la diapositiva specificata è nascosta durante la presentazione. |
| [setHidden(boolean value)](#setHidden-boolean-) | Determina se la diapositiva specificata è nascosta durante la presentazione. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Restituisce un oggetto immagine con scala personalizzata. |
| [getImage()](#getImage--) | Restituisce un oggetto Thumbnail Image (20% della dimensione reale). |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | Restituisce un oggetto immagine con dimensione specificata. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Restituisce un oggetto Thumbnail tiff bitmap con parametri specificati. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Restituisce un oggetto Thumbnail Bitmap. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Restituisce un oggetto Thumbnail Bitmap con scala personalizzata. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Restituisce un oggetto Thumbnail Bitmap con dimensione specificata. |
| [getLayoutSlide()](#getLayoutSlide--) | Restituisce o imposta il layout slide per la diapositiva corrente. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Restituisce o imposta il layout slide per la diapositiva corrente. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Consente di accedere alla diapositiva delle note, aggiungerla e rimuoverla. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Restituisce tutti i commenti della diapositiva aggiunti da uno specifico autore. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Salva il contenuto della diapositiva come file SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Salva il contenuto della diapositiva come file SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Salva il contenuto della diapositiva come file EMF. |
| [remove()](#remove--) | Rimuove la diapositiva dalla presentazione. |
| [reset()](#reset--) | Reimposta posizione, dimensione e formattazione di ogni forma che ha un prototipo su LayoutSlide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

Restituisce il gestore HeaderFooter della diapositiva. Solo lettura [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Restituisce:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

Restituisce il numero della diapositiva. L'indice della diapositiva nella collezione [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) è sempre pari a SlideNumber - 1. Lettura/Scrittura int.

**Restituisce:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

Restituisce il numero della diapositiva. L'indice della diapositiva nella collezione [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) è sempre pari a SlideNumber - 1. Lettura/Scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Determina se la diapositiva specificata è nascosta durante la presentazione. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Determina se la diapositiva specificata è nascosta durante la presentazione. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

Restituisce un oggetto immagine con scala personalizzata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scaleX | float | Il valore con cui scalare questa Thumbnail nell'asse x. |
| scaleY | float | Il valore con cui scalare questa Thumbnail nell'asse y. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Restituisce un oggetto Thumbnail Image (20% della dimensione reale).

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage
### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public abstract IImage getImage(Dimension imageSize)
```

Restituisce un oggetto immagine con dimensione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageSize | java.awt.Dimension | Dimensione dell'immagine da creare. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

Restituisce un oggetto Thumbnail tiff bitmap con parametri specificati.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Opzioni Tiff. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

Restituisce un oggetto Thumbnail Bitmap.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni di rendering. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Restituisce un oggetto Thumbnail Bitmap con scala personalizzata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni di rendering. |
| scaleX | float | Il valore con cui scalare questa Thumbnail nell'asse x. |
| scaleY | float | Il valore con cui scalare questa Thumbnail nell'asse y. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage getImage(IRenderingOptions options, Dimension imageSize)
```

Restituisce un oggetto Thumbnail Bitmap con dimensione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni di rendering. |
| imageSize | java.awt.Dimension | Dimensione dell'immagine da creare. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

Restituisce o imposta il layout slide per la diapositiva corrente. Lettura/Scrittura [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

Restituisce o imposta il layout slide per la diapositiva corrente. Lettura/Scrittura [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

Consente di accedere alla diapositiva delle note, aggiungerla e rimuoverla. Solo lettura [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Restituisce:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

Restituisce tutti i commenti della diapositiva aggiunti da uno specifico autore.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Autore dei commenti da cercare o null per restituire tutti i commenti. |

**Restituisce:**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Salva il contenuto della diapositiva come file SVG.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream di destinazione |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Salva il contenuto della diapositiva come file SVG.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream di destinazione |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opzioni di generazione SVG |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

Salva il contenuto della diapositiva come file EMF.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream di destinazione |
### remove() {#remove--}
```
public abstract void remove()
```

Rimuove la diapositiva dalla presentazione.
### reset() {#reset--}
```
public abstract void reset()
```

Reimposta posizione, dimensione e formattazione di ogni forma che ha un prototipo su LayoutSlide.