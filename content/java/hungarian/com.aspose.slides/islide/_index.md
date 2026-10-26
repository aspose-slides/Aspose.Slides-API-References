---
title: ISlide
second_title: Aspose.Slides Java API referencia
description: Egy diát képvisel egy bemutatóban.
type: docs
url: /hu/com.aspose.slides/islide/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

Egy dia a bemutatóban.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a diában található HeaderFooter menedzsert. |
| [getSlideNumber()](#getSlideNumber--) | Visszaadja a dia számát. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Visszaadja a dia számát. |
| [getHidden()](#getHidden--) | Megállapítja, hogy a megadott dia rejtett-e a diavetítés során. |
| [setHidden(boolean value)](#setHidden-boolean-) | Megállapítja, hogy a megadott dia rejtett-e a diavetítés során. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Visszaad egy képöbjektumot egyedi méretezéssel. |
| [getImage()](#getImage--) | Visszaad egy miniaturált képobjektumot (20% a valós méretből). |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | Visszaad egy képöbjektumot a megadott mérettel. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Visszaad egy miniaturált tiff bitmap objektumot a megadott paraméterekkel. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Visszaad egy miniaturált Bitmap objektumot. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Visszaad egy miniaturált Bitmap objektumot egyedi méretezéssel. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Visszaad egy miniaturált Bitmap objektumot a megadott mérettel. |
| [getLayoutSlide()](#getLayoutSlide--) | Visszaadja vagy beállítja az aktuális dia elrendezési diáját. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Visszaadja vagy beállítja az aktuális dia elrendezési diáját. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Lehetővé teszi a jegyzetdiához való hozzáférést, hozzáadását és eltávolítását. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Visszaadja az adott szerző által hozzáadott összes dia kommentet. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Elmenti a dia tartalmát SVG fájlként. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Elmenti a dia tartalmát SVG fájlként. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Elmenti a dia tartalmát EMF fájlként. |
| [remove()](#remove--) | Eltávolítja a diát a bemutatóból. |
| [reset()](#reset--) | Visszaállítja az összes alakzat pozícióját, méretét és formázását, amelynek prototípusa a LayoutSlide-on van. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

Visszaadja a diában található HeaderFooter menedzsert. Csak olvasható [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Visszatér:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

Visszaadja a dia számát. A [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) gyűjteményben a dia indexe mindig egyenlő a SlideNumber - 1 értékkel. Olvasás/írás int.

**Visszatér:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

Visszaadja a dia számát. A [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) gyűjteményben a dia indexe mindig egyenlő a SlideNumber - 1 értékkel. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Megállapítja, hogy a megadott dia rejtett-e a diavetítés során. Olvasás/írás boolean.

**Visszatér:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Megállapítja, hogy a megadott dia rejtett-e a diavetítés során. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

Visszaad egy képöbjektumot egyedi méretezéssel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| scaleX | float | Az a érték, amellyel a miniaturát az x-tengelyen méretezi. |
| scaleY | float | Az a érték, amellyel a miniaturát az y-tengelyen méretezi. |

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Visszaad egy miniaturált képobjektumot (20% a valós méretből).

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage
### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public abstract IImage getImage(Dimension imageSize)
```

Visszaad egy képöbjektumot a megadott mérettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| imageSize | java.awt.Dimension | A létrehozandó kép mérete. |

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

Visszaad egy miniaturált tiff bitmap objektumot a megadott paraméterekkel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff beállítások. |

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

Visszaad egy miniaturált Bitmap objektumot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderelési beállítások. |

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Visszaad egy miniaturált Bitmap objektumot egyedi méretezéssel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderelési beállítások. |
| scaleX | float | Az a érték, amellyel a miniaturát az x-tengelyen méretezi. |
| scaleY | float | Az a érték, amellyel a miniaturát az y-tengelyen méretezi. |

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage getImage(IRenderingOptions options, Dimension imageSize)
```

Visszaad egy miniaturált Bitmap objektumot a megadott mérettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderelési beállítások. |
| imageSize | java.awt.Dimension | A létrehozandó kép mérete. |

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

Visszaadja vagy beállítja az aktuális dia elrendezési diáját. Olvasás/írás [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Visszatér:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

Visszaadja vagy beállítja az aktuális dia elrendezési diáját. Olvasás/írás [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

Lehetővé teszi a jegyzetdia elérését, hozzáadását és eltávolítását. Csak olvasható [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Visszatér:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

Visszaadja az adott szerző által hozzáadott összes dia megjegyzést.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | A megtalálandó megjegyzések szerzője, vagy null, ha az összes megjegyzést vissza akarja kapni. |

**Visszatér:**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Elmenti a dia tartalmát SVG fájlként.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Cél stream |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Elmenti a dia tartalmát SVG fájlként.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Cél stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generálási beállítások |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

Elmenti a dia tartalmát EMF fájlként.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Cél stream |
### remove() {#remove--}
```
public abstract void remove()
```

Eltávolítja a diát a bemutatóból.
### reset() {#reset--}
```
public abstract void reset()
```

Visszaállítja minden alakzat pozícióját, méretét és formázását, amelynek prototípusa a LayoutSlide-on van.