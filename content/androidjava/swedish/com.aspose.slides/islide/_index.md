---
title: ISlide
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en bild i en presentation.
type: docs
url: /sv/com.aspose.slides/islide/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

Representerar en bild i en presentation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returnerar HeaderFooter manager för bilden. |
| [getSlideNumber()](#getSlideNumber--) | Returnerar bildens nummer. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Returnerar bildens nummer. |
| [getHidden()](#getHidden--) | Avgör om den angivna bilden är dold under ett bildspel. |
| [setHidden(boolean value)](#setHidden-boolean-) | Avgör om den angivna bilden är dold under ett bildspel. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Returnerar ett bildobjekt med anpassad skalning. |
| [getImage()](#getImage--) | Returnerar ett Thumbnail Image object (20% av verklig storlek). |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Returnerar ett bildobjekt med angiven storlek. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Returnerar ett Thumbnail tiff-bitmap-objekt med angivna parametrar. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Returnerar ett Thumbnail Bitmap-objekt. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Returnerar ett Thumbnail Bitmap-objekt med anpassad skalning. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Returnerar ett Thumbnail Bitmap-objekt med angiven storlek. |
| [getLayoutSlide()](#getLayoutSlide--) | Returnerar eller anger layoutbilden för den aktuella bilden. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Returnerar eller anger layoutbilden för den aktuella bilden. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Tillåter åtkomst till notes slide, lägga till och ta bort den. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Returnerar alla bildkommentarer som lagts till av en specifik författare. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Sparar bildens innehåll som en SVG-fil. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Sparar bildens innehåll som en SVG-fil. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Sparar bildens innehåll som en EMF-fil. |
| [remove()](#remove--) | Tar bort bilden från presentationen. |
| [reset()](#reset--) | Återställer position, storlek och formatering för varje form som har en prototyp på LayoutSlide. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

Returnerar HeaderFooter manager för bilden. Skrivskyddad [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Returnerar:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

Returnerar bildens nummer. Index för bilden i [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides)-samlingen är alltid lika med SlideNumber - 1. Läs/skriv int.

**Returnerar:**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

Returnerar bildens nummer. Index för bilden i [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides)-samlingen är alltid lika med SlideNumber - 1. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Avgör om den angivna bilden är dold under ett bildspel. Läs/skriv boolean.

**Returnerar:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Avgör om den angivna bilden är dold under ett bildspel. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

Returnerar ett bildobjekt med anpassad skalning.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scaleX | float | Värdet som används för att skala detta Thumbnail i x-axelns riktning. |
| scaleY | float | Värdet som används för att skala detta Thumbnail i y-axelns riktning. |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Image object android.graphics.Bitmap

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Returnerar ett Thumbnail Image object (20% av verklig storlek).

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Image object android.graphics.Bitmap

### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(Size imageSize)
```

Returnerar ett bildobjekt med angiven storlek.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Storlek på bilden som ska skapas. |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

Returnerar ett Thumbnail tiff-bitmap-objekt med angivna parametrar.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff-alternativ. |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

Returnerar ett Thumbnail Bitmap-objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderingsalternativ. |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Returnerar ett Thumbnail Bitmap-objekt med anpassad skalning.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderingsalternativ. |
| scaleX | float | Värdet som används för att skala detta Thumbnail i x-axelns riktning. |
| scaleY | float | Värdet som används för att skala detta Thumbnail i y-axelns riktning. |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(IRenderingOptions options, Size imageSize)
```

Returnerar ett Thumbnail Bitmap-objekt med angiven storlek.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderingsalternativ. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Storlek på bilden som ska skapas. |

**Returnerar:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

Returnerar eller anger layoutbilden för den aktuella bilden. Läs/skriv [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

Returnerar eller anger layoutbilden för den aktuella bilden. Läs/skriv [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

Tillåter åtkomst till notes slide, lägga till och ta bort den. Skrivskyddad [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Returnerar:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

Returnerar alla slide-kommentarer som lagts till av en specifik författare.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Författare till kommentarer att söka eller null för att returnera alla kommentarer. |

**Returnerar:**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Sparar bildens innehåll som en SVG-fil.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Målsström |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Sparar bildens innehåll som en SVG-fil.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Målsström |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG-genereringsalternativ |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

Sparar bildens innehåll som en EMF-fil.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Målsström |

### remove() {#remove--}
```
public abstract void remove()
```

Tar bort bilden från presentationen.

### reset() {#reset--}
```
public abstract void reset()
```

Återställer position, storlek och formatering för varje form som har en prototyp på LayoutSlide.