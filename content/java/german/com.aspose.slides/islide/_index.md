---
title: ISlide
second_title: Aspose.Slides für Java API Referenz
description: Stellt eine Folie in einer Präsentation dar.
type: docs
url: /de/com.aspose.slides/islide/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

Stellt eine Folie in einer Präsentation dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Gibt den HeaderFooter-Manager der Folie zurück. |
| [getSlideNumber()](#getSlideNumber--) | Gibt die Nummer der Folie zurück. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Gibt die Nummer der Folie zurück. |
| [getHidden()](#getHidden--) | Bestimmt, ob die angegebene Folie während einer Vorführung ausgeblendet ist. |
| [setHidden(boolean value)](#setHidden-boolean-) | Bestimmt, ob die angegebene Folie während einer Vorführung ausgeblendet ist. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Gibt ein Bildobjekt mit benutzerdefinierter Skalierung zurück. |
| [getImage()](#getImage--) | Gibt ein Thumbnail-Bildobjekt (20 % der Originalgröße) zurück. |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | Gibt ein Bildobjekt mit der angegebenen Größe zurück. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Gibt ein Thumbnail-TIFF-Bitmap-Objekt mit den angegebenen Parametern zurück. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Gibt ein Thumbnail-Bitmap-Objekt zurück. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Gibt ein Thumbnail-Bitmap-Objekt mit benutzerdefinierter Skalierung zurück. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Gibt ein Thumbnail-Bitmap-Objekt mit der angegebenen Größe zurück. |
| [getLayoutSlide()](#getLayoutSlide--) | Gibt das Layout der aktuellen Folie zurück oder legt es fest. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Gibt das Layout der aktuellen Folie zurück oder legt es fest. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Ermöglicht den Zugriff auf die Notizfolie, Hinzufügen und Entfernen. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Gibt alle Folienkommentare zurück, die von einem bestimmten Autor hinzugefügt wurden. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Speichert den Folieninhalt als SVG-Datei. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Speichert den Folieninhalt als SVG-Datei. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Speichert den Folieninhalt als EMF-Datei. |
| [remove()](#remove--) | Entfernt die Folie aus der Präsentation. |
| [reset()](#reset--) | Setzt Position, Größe und Formatierung aller Formen zurück, die auf LayoutSlide ein Prototyp haben. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

Gibt den HeaderFooter-Manager der Folie zurück. Nur lesbar [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Rückgabe:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

Gibt die Nummer der Folie zurück. Der Index der Folie in der [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides)-Sammlung ist stets gleich SlideNumber - 1. Lesen/Schreiben int.

**Rückgabe:**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

Gibt die Nummer der Folie zurück. Der Index der Folie in der [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides)-Sammlung ist stets gleich SlideNumber - 1. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Bestimmt, ob die angegebene Folie während einer Vorführung ausgeblendet ist. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Bestimmt, ob die angegebene Folie während einer Vorführung ausgeblendet ist. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

Gibt ein Bildobjekt mit benutzerdefinierter Skalierung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scaleX | float | Der Wert, um den dieses Thumbnail in x-Richtung skaliert wird. |
| scaleY | float | Der Wert, um den dieses Thumbnail in y-Richtung skaliert wird. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Bildobjekt java.awt.image.BufferedImage

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Gibt ein Thumbnail-Bildobjekt (20 % der Originalgröße) zurück.

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Bildobjekt java.awt.image.BufferedImage

### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public abstract IImage getImage(Dimension imageSize)
```

Gibt ein Bildobjekt mit der angegebenen Größe zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageSize | java.awt.Dimension | Größe des zu erstellenden Bildes. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Bitmap-Objekt.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

Gibt ein Thumbnail-TIFF-Bitmap-Objekt mit den angegebenen Parametern zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff-Optionen. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Bildobjekt.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

Gibt ein Thumbnail-Bitmap-Objekt zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderoptionen. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Bitmap-Objekte.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Gibt ein Thumbnail-Bitmap-Objekt mit benutzerdefinierter Skalierung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderoptionen. |
| scaleX | float | Der Wert, um den dieses Thumbnail in x-Richtung skaliert wird. |
| scaleY | float | Der Wert, um den dieses Thumbnail in y-Richtung skaliert wird. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Bitmap-Objekte.

### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage getImage(IRenderingOptions options, Dimension imageSize)
```

Gibt ein Thumbnail-Bitmap-Objekt mit der angegebenen Größe zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderoptionen. |
| imageSize | java.awt.Dimension | Größe des zu erstellenden Bildes. |

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage) - Bitmap-Objekte.

### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

Gibt das Layout der aktuellen Folie zurück oder legt es fest. Lesen/Schreiben [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Rückgabe:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

Gibt das Layout der aktuellen Folie zurück oder legt es fest. Lesen/Schreiben [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

Ermöglicht den Zugriff auf die Notizfolie, Hinzufügen und Entfernen. Nur lesbar [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Rückgabe:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

Gibt alle Folienkommentare zurück, die von einem bestimmten Autor hinzugefügt wurden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Autor der zu findenden Kommentare oder null, um alle Kommentare zurückzugeben. |

**Rückgabe:**
com.aspose.slides.IComment[] - Array von [IComment](../../com.aspose.slides/icomment).

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Speichert den Folieninhalt als SVG-Datei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ziel-Stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Speichert den Folieninhalt als SVG-Datei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ziel-Stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG-Generierungsoptionen |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

Speichert den Folieninhalt als EMF-Datei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.OutputStream | Ziel-Stream |

### remove() {#remove--}
```
public abstract void remove()
```

Entfernt die Folie aus der Präsentation.

### reset() {#reset--}
```
public abstract void reset()
```

Setzt Position, Größe und Formatierung aller Formen zurück, die auf LayoutSlide ein Prototyp haben.