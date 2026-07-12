---
title: ISlide
second_title: Aspose.Slides für Android via Java API Referenz
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
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Gibt den HeaderFooter-Manager der Folie zurück. Nur-Lesen [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager). |
| [getSlideNumber()](#getSlideNumber--) | Gibt die Foliennummer zurück. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Gibt die Foliennummer zurück. |
| [getHidden()](#getHidden--) | Bestimmt, ob die angegebene Folie während einer Bildschirmerkennung ausgeblendet ist. |
| [setHidden(boolean value)](#setHidden-boolean-) | Bestimmt, ob die angegebene Folie während einer Bildschirmerkennung ausgeblendet ist. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Gibt ein Bildobjekt mit benutzerdefinierter Skalierung zurück. |
| [getImage()](#getImage--) | Gibt ein Thumbnail-Bildobjekt zurück (20 % der Originalgröße). |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Gibt ein Bildobjekt mit angegebener Größe zurück. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Gibt ein Thumbnail-Tiff-Bitmap-Objekt mit angegebenen Parametern zurück. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Gibt ein Thumbnail-Bitmap-Objekt zurück. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Gibt ein Thumbnail-Bitmap-Objekt mit benutzerdefinierter Skalierung zurück. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Gibt ein Thumbnail-Bitmap-Objekt mit angegebener Größe zurück. |
| [getLayoutSlide()](#getLayoutSlide--) | Gibt das Layout der Folie für die aktuelle Folie zurück oder legt es fest. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Gibt das Layout der Folie für die aktuelle Folie zurück oder legt es fest. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Ermöglicht den Zugriff auf die Notizfolie, deren Hinzufügen und Entfernen. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Gibt alle Folienkommentare zurück, die von einem bestimmten Autor hinzugefügt wurden. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Speichert den Folieninhalt als SVG-Datei. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Speichert den Folieninhalt als SVG-Datei. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Speichert den Folieninhalt als EMF-Datei. |
| [remove()](#remove--) | Entfernt die Folie aus der Präsentation. |
| [reset()](#reset--) | Setzt Position, Größe und Formatierung aller Formen zurück, die auf LayoutSlide ein Prototype besitzen. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

**Rückgabewert:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

Gibt die Foliennummer zurück. Der Index der Folie in der [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides)-Sammlung ist immer gleich SlideNumber - 1. Lese/Schreib int.

**Rückgabewert:**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

Gibt die Foliennummer zurück. Der Index der Folie in der [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides)-Sammlung ist immer gleich SlideNumber - 1. Lese/Schreib int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Bestimmt, ob die angegebene Folie während einer Bildschirmerkennung ausgeblendet ist. Lese/Schreib boolean.

**Rückgabewert:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Bestimmt, ob die angegebene Folie während einer Bildschirmerkennung ausgeblendet ist. Lese/Schreib boolean.

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

**Rückgabewert:**
[IImage](../../com.aspose.slides/iimage) - Bildobjekt android.graphics.Bitmap

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Gibt ein Thumbnail-Bildobjekt zurück (20 % der Originalgröße).

**Rückgabewert:**
[IImage](../../com.aspose.slides/iimage) - Bildobjekt android.graphics.Bitmap

### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(Size imageSize)
```

Gibt ein Bildobjekt mit angegebener Größe zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Größe des zu erstellenden Bildes. |

**Rückgabewert:**
[IImage](../../com.aspose.slides/iimage) - Bitmap-Objekt.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

Gibt ein Thumbnail-Tiff-Bitmap-Objekt mit angegebenen Parametern zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff-Optionen. |

**Rückgabewert:**
[IImage](../../com.aspose.slides/iimage) - Bildobjekt.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

Gibt ein Thumbnail-Bitmap-Objekt zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-Optionen. |

**Rückgabewert:**
[IImage](../../com.aspose.slides/iimage) - Bitmap-Objekte.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Gibt ein Thumbnail-Bitmap-Objekt mit benutzerdefinierter Skalierung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-Optionen. |
| scaleX | float | Der Wert, um den dieses Thumbnail in x-Richtung skaliert wird. |
| scaleY | float | Der Wert, um den dieses Thumbnail in y-Richtung skaliert wird. |

**Rückgabewert:**
[IImage](../../com.aspose.slides/iimage) - Bitmap-Objekte.

### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(IRenderingOptions options, Size imageSize)
```

Gibt ein Thumbnail-Bitmap-Objekt mit angegebener Größe zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-Optionen. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Größe des zu erstellenden Bildes. |

**Rückgabewert:**
[IImage](../../com.aspose.slides/iimage) - Bitmap-Objekte.

### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

Gibt das Layout der Folie für die aktuelle Folie zurück oder legt es fest. Lese/Schreib [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Rückgabewert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

Gibt das Layout der Folie für die aktuelle Folie zurück oder legt es fest. Lese/Schreib [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

Ermöglicht den Zugriff auf die Notizfolie, deren Hinzufügen und Entfernen. Nur-Lesen [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Rückgabewert:**
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

**Rückgabewert:**
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

Setzt Position, Größe und Formatierung aller Formen zurück, die auf LayoutSlide ein Prototype besitzen.