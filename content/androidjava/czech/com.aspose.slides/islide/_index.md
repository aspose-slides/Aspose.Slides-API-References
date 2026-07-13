---
title: ISlide
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Představuje snímek v prezentaci.
type: docs
url: /cs/com.aspose.slides/islide/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

Představuje snímek v prezentaci.
## Metody

| Metoda | Popis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Vrací správce HeaderFooter snímku. |
| [getSlideNumber()](#getSlideNumber--) | Vrací číslo snímku. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Vrací číslo snímku. |
| [getHidden()](#getHidden--) | Určuje, zda je zadaný snímek během prezentace skrytý. |
| [setHidden(boolean value)](#setHidden-boolean-) | Určuje, zda je zadaný snímek během prezentace skrytý. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Vrací objekt obrázku s vlastním měřítkem. |
| [getImage()](#getImage--) | Vrací objekt miniatury Image (20 % skutečné velikosti). |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Vrací objekt obrázku se zadanou velikostí. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Vrací objekt miniatury tiff bitmapy se zadanými parametry. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Vrací objekt miniatury Bitmap. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Vrací objekt miniatury Bitmap s vlastním měřítkem. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Vrací objekt miniatury Bitmap se zadanou velikostí. |
| [getLayoutSlide()](#getLayoutSlide--) | Vrací nebo nastavuje rozložení snímku pro aktuální snímek. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Vrací nebo nastavuje rozložení snímku pro aktuální snímek. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Umožňuje přístup k poznámkovému snímku, jeho přidání a odebrání. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Vrací všechny komentáře snímku přidané konkrétním autorem. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Ukládá obsah snímku jako soubor SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Ukládá obsah snímku jako soubor SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Ukládá obsah snímku jako soubor EMF. |
| [remove()](#remove--) | Odstraňuje snímek z prezentace. |
| [reset()](#reset--) | Resetuje pozici, velikost a formátování každého tvaru, který má prototyp na LayoutSlide. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```


Vrací správce HeaderFooter snímku. Pouze pro čtení [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Vrací:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```


Vrací číslo snímku. Index snímku v kolekci [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) je vždy roven SlideNumber - 1. Čtení/zápis int.

**Vrací:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```


Vrací číslo snímku. Index snímku v kolekci [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) je vždy roven SlideNumber - 1. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```


Určuje, zda je zadaný snímek během prezentace skrytý. Čtení/zápis boolean.

**Vrací:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```


Určuje, zda je zadaný snímek během prezentace skrytý. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```


Vrací objekt obrázku s vlastním měřítkem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| scaleX | float | Hodnota, o kterou se má tato miniatura měřít v ose x. |
| scaleY | float | Hodnota, o kterou se má tato miniatura měřít v ose y. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Image object android.graphics.Bitmap
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Vrací objekt miniatury Image (20 % skutečné velikosti).

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Image object android.graphics.Bitmap
### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(Size imageSize)
```


Vrací objekt obrázku se zadanou velikostí.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Velikost obrázku k vytvoření. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```


Vrací objekt miniatury tiff bitmapy se zadanými parametry.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Možnosti Tiff. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```


Vrací objekt miniatury Bitmap.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti vykreslení. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```


Vrací objekt miniatury Bitmap s vlastním měřítkem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti vykreslení. |
| scaleX | float | Hodnota, o kterou se má tato miniatura měřít v ose x. |
| scaleY | float | Hodnota, o kterou se má tato miniatura měřít v ose y. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(IRenderingOptions options, Size imageSize)
```


Vrací objekt miniatury Bitmap se zadanou velikostí.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti vykreslení. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Velikost obrázku k vytvoření. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```


Vrací nebo nastavuje rozložení snímku pro aktuální snímek. Čtení/zápis [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Vrací:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```


Vrací nebo nastavuje rozložení snímku pro aktuální snímek. Čtení/zápis [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```


Umožňuje přístup k poznámkovému snímku, jeho přidání a odebrání. Pouze pro čtení [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Vrací:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```


Vrací všechny komentáře snímku přidané konkrétním autorem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Autor komentářů k nalezení nebo null pro vrácení všech komentářů. |

**Vrací:**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```


Ukládá obsah snímku jako soubor SVG.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Cílový stream |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```


Ukládá obsah snímku jako soubor SVG.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Cílový stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Možnosti generování SVG |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


Ukládá obsah snímku jako soubor EMF.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Cílový stream |
### remove() {#remove--}
```
public abstract void remove()
```


Odstraňuje snímek z prezentace.
### reset() {#reset--}
```
public abstract void reset()
```


Resetuje pozici, velikost a formátování každého tvaru, který má prototyp na LayoutSlide.