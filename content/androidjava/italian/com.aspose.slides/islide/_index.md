---
title: ISlide
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta una diapositiva in una presentazione.
type: docs
url: /it/com.aspose.slides/islide/
---
**Tutte le interfacce implementate:**
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
| [getHidden()](#getHidden--) | Determina se la diapositiva specificata è nascosta durante una presentazione. |
| [setHidden(boolean value)](#setHidden-boolean-) | Determina se la diapositiva specificata è nascosta durante una presentazione. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Restituisce un oggetto immagine con scala personalizzata. |
| [getImage()](#getImage--) | Restituisce un oggetto Thumbnail Image (20% della dimensione reale). |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Restituisce un oggetto immagine con dimensione specificata. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Restituisce un oggetto Thumbnail tiff bitmap con parametri specificati. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Restituisce un oggetto Thumbnail Bitmap. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Restituisce un oggetto Thumbnail Bitmap con scala personalizzata. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Restituisce un oggetto Thumbnail Bitmap con dimensione specificata. |
| [getLayoutSlide()](#getLayoutSlide--) | Restituisce o imposta la diapositiva di layout per la diapositiva corrente. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Restituisce o imposta la diapositiva di layout per la diapositiva corrente. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Consente di accedere alla diapositiva delle note, aggiungerla e rimuoverla. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Restituisce tutti i commenti della diapositiva aggiunti da un autore specifico. |
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

Restituisce il numero della diapositiva. L'indice della diapositiva nella collezione [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) è sempre uguale a SlideNumber - 1. Lettura/scrittura int.

**Restituisce:**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

Restituisce il numero della diapositiva. L'indice della diapositiva nella collezione [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) è sempre uguale a SlideNumber - 1. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Determina se la diapositiva specificata è nascosta durante una presentazione. Lettura/scrittura boolean.

**Restituisce:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Determina se la diapositiva specificata è nascosta durante una presentazione. Lettura/scrittura boolean.

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
| scaleX | float | Il valore con cui scalare questa Thumbnail lungo l'asse x. |
| scaleY | float | Il valore con cui scalare questa Thumbnail lungo l'asse y. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - oggetto Image android.graphics.Bitmap

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Restituisce un oggetto Thumbnail Image (20% della dimensione reale).

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - oggetto Image android.graphics.Bitmap

### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(Size imageSize)
```

Restituisce un oggetto immagine con dimensione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Dimensione dell'immagine da creare. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - oggetto Bitmap.

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
[IImage](../../com.aspose.slides/iimage) - oggetto Image.

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
[IImage](../../com.aspose.slides/iimage) - oggetti Bitmap.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Restituisce un oggetto Thumbnail Bitmap con scala personalizzata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni di rendering. |
| scaleX | float | Il valore con cui scalare questa Thumbnail lungo l'asse x. |
| scaleY | float | Il valore con cui scalare questa Thumbnail lungo l'asse y. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - oggetti Bitmap.

### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(IRenderingOptions options, Size imageSize)
```

Restituisce un oggetto Thumbnail Bitmap con dimensione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni di rendering. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Dimensione dell'immagine da creare. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - oggetti Bitmap.

### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

Restituisce o imposta la diapositiva di layout per la diapositiva corrente. Lettura/scrittura [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

Restituisce o imposta la diapositiva di layout per la diapositiva corrente. Lettura/scrittura [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

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

Restituisce tutti i commenti della diapositiva aggiunti da un autore specifico.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Autore dei commenti da trovare o null per restituire tutti i commenti. |

**Restituisce:**
com.aspose.slides.IComment[] - Array di [IComment](../../com.aspose.slides/icomment).

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