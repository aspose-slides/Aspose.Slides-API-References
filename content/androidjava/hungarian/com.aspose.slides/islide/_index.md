---
title: ISlide
second_title: Aspose.Slides Androidra a Java API hivatkozás szerint
description: Egy diát képvisel egy prezentációban.
type: docs
url: /hu/com.aspose.slides/islide/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

Diát képvisel egy prezentációban.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a dia HeaderFooter kezelőjét. |
| [getSlideNumber()](#getSlideNumber--) | Visszaadja a dia számát. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Visszaadja a dia számát. |
| [getHidden()](#getHidden--) | Megállapítja, hogy a megadott dia rejtett-e a diavetítés során. |
| [setHidden(boolean value)](#setHidden-boolean-) | Megállapítja, hogy a megadott dia rejtett-e a diavetítés során. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Visszaad egy képet objektumot egyéni méretezéssel. |
| [getImage()](#getImage--) | Visszaad egy bélyegkép képet (20% a valódi méretből). |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Visszaad egy képet objektumot a megadott mérettel. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Visszaad egy bélyegkép tiff bitmap objektumot a megadott paraméterekkel. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Visszaad egy bélyegkép Bitmap objektumot. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Visszaad egy bélyegkép Bitmap objektumot egyéni méretezéssel. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Visszaad egy bélyegkép Bitmap objektumot a megadott mérettel. |
| [getLayoutSlide()](#getLayoutSlide--) | Visszaadja vagy beállítja az aktuális dia elrendezését. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Visszaadja vagy beállítja az aktuális dia elrendezését. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Lehetővé teszi a jegyzetdia elérését, hozzáadását és eltávolítását. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Visszaadja az adott szerző által hozzáadott összes dia megjegyzést. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | A dia tartalmát SVG fájlként menti. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | A dia tartalmát SVG fájlként menti. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | A dia tartalmát EMF fájlként menti. |
| [remove()](#remove--) | Eltávolítja a diát a prezentációból. |
| [reset()](#reset--) | Alaphelyzetbe állítja minden alakzat pozícióját, méretét és formázását, amelynek prototípusa a LayoutSlide. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

Visszaadja a dia HeaderFooter kezelőjét. Csak-olvasás [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Visszatér:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

Visszaadja a dia számát. A [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) gyűjteményben a dia indexe mindig egyenlő a SlideNumber - 1 értékével. Olvasás-írás int.

**Visszatér:**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

Beállítja a dia számát. A [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) gyűjteményben a dia indexe mindig egyenlő a SlideNumber - 1 értékével. Olvasás-írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Megállapítja, hogy a megadott dia rejtett-e a diavetítés során. Olvasás-írás boolean.

**Visszatér:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Megállapítja, hogy a megadott dia rejtett-e a diavetítés során. Olvasás-írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

Visszaad egy képet objektumot egyéni méretezéssel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| scaleX | float | Az érték, amellyel a bélyegkép X-tengelyen skálázásra kerül. |
| scaleY | float | Az érték, amellyel a bélyegkép Y-tengelyen skálázásra kerül. |

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) - Image object android.graphics.Bitmap

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Visszaad egy bélyegkép képet (20% a valódi méretből).

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) - Image object android.graphics.Bitmap

### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(Size imageSize)
```

Visszaad egy képet objektumot a megadott mérettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | A létrehozandó kép mérete. |

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

Visszaad egy bélyegkép tiff bitmap objektumot a megadott paraméterekkel.

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

Visszaad egy bélyegkép Bitmap objektumot.

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

Visszaad egy bélyegkép Bitmap objektumot egyéni méretezéssel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderelési beállítások. |
| scaleX | float | Az érték, amellyel a bélyegkép X-tengelyen skálázásra kerül. |
| scaleY | float | Az érték, amellyel a bélyegkép Y-tengelyen skálázásra kerül. |

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(IRenderingOptions options, Size imageSize)
```

Visszaad egy bélyegkép Bitmap objektumot a megadott mérettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderelési beállítások. |
| imageSize | [Size](../../com.aspose.slides.android/size) | A létrehozandó kép mérete. |

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

Visszaadja vagy beállítja az aktuális dia elrendezését. Olvasás-írás [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Visszatér:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

Visszaadja vagy beállítja az aktuális dia elrendezését. Olvasás-írás [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

Lehetővé teszi a jegyzetdia elérését, hozzáadását és eltávolítását. Csak-olvasás [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Visszatér:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

Visszaadja a megadott szerző által hozzáadott összes dia megjegyzést.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | A megjegyzések szerzője, vagy null, ha az összes megjegyzés visszatérését szeretnénk. |

**Visszatér:**
com.aspose.slides.IComment[] - Tömbje a [IComment](../../com.aspose.slides/icomment).

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

A dia tartalmát SVG fájlként menti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Célfolyam |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

A dia tartalmát SVG fájlként menti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Célfolyam |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generálási beállítások |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

A dia tartalmát EMF fájlként menti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Célfolyam |

### remove() {#remove--}
```
public abstract void remove()
```

Eltávolítja a diát a prezentációból.

### reset() {#reset--}
```
public abstract void reset()
```

Alaphelyzetbe állítja minden alakzat pozícióját, méretét és formázását, amelynek prototípusa a LayoutSlide.