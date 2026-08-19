---
title: ISlide
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje snímek v prezentaci.
type: docs
url: /cs/com.aspose.slides/islide/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

Represents a slide in a presentation.
## Metody

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Vrací správce HeaderFooter snímku. |
| [getSlideNumber()](#getSlideNumber--) | Vrací číslo snímku. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Vrací číslo snímku. |
| [getHidden()](#getHidden--) | Určuje, zda je daný snímek skryt během prezentace. |
| [setHidden(boolean value)](#setHidden-boolean-) | Určuje, zda je daný snímek skryt během prezentace. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Vrací objekt obrázku s vlastním měřítkem. |
| [getImage()](#getImage--) | Vrací miniaturu obrázku (20 % skutečné velikosti). |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | Vrací objekt obrázku se zadanou velikostí. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Vrací miniaturu TIFF bitmapy se zadanými parametry. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Vrací miniaturu bitmapy. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Vrací miniaturu bitmapy s vlastním měřítkem. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Vrací miniaturu bitmapy se zadanou velikostí. |
| [getLayoutSlide()](#getLayoutSlide--) | Vrací nebo nastavuje rozložení snímku pro aktuální snímek. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Vrací nebo nastavuje rozložení snímku pro aktuální snímek. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Umožňuje přístup k poznámkovému snímku, přidání a odebrání. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Vrací všechny komentáře ke snímku přidané konkrétním autorem. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Uloží obsah snímku jako soubor SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Uloží obsah snímku jako soubor SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Uloží obsah snímku jako soubor EMF. |
| [remove()](#remove--) | Odstraní snímek z prezentace. |
| [reset()](#reset--) | Obnoví pozici, velikost a formátování každého tvaru, který má prototyp na LayoutSlide. |
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

Vrací číslo snímku. Index snímku ve sbírce [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) je vždy roven SlideNumber - 1. Čtení/zápis int.

**Vrací:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

Vrací číslo snímku. Index snímku ve sbírce [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) je vždy roven SlideNumber - 1. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Určuje, zda je daný snímek skryt během prezentace. Čtení/zápis boolean.

**Vrací:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Určuje, zda je daný snímek skryt během prezentace. Čtení/zápis boolean.

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
| scaleX | float | Hodnota, o kterou se má miniatura škálovat ve směru osy x. |
| scaleY | float | Hodnota, o kterou se má miniatura škálovat ve směru osy y. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Objekt obrázku java.awt.image.BufferedImage
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Vrací miniaturu obrázku (20 % skutečné velikosti).

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Objekt obrázku java.awt.image.BufferedImage
### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public abstract IImage getImage(Dimension imageSize)
```

Vrací objekt obrázku se zadanou velikostí.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| imageSize | java.awt.Dimension | Velikost obrázku, který se má vytvořit. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Objekt bitmapy.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

Vrací miniaturu TIFF bitmapy se zadanými parametry.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Možnosti TIFF. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Objekt obrázku.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

Vrací miniaturu bitmapy.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti vykreslení. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Objekty bitmap.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Vrací miniaturu bitmapy s vlastním měřítkem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti vykreslení. |
| scaleX | float | Hodnota, o kterou se má miniatura škálovat ve směru osy x. |
| scaleY | float | Hodnota, o kterou se má miniatura škálovat ve směru osy y. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Objekty bitmap.
### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage getImage(IRenderingOptions options, Dimension imageSize)
```

Vrací miniaturu bitmapy se zadanou velikostí.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti vykreslení. |
| imageSize | java.awt.Dimension | Velikost obrázku, který se má vytvořit. |

**Vrací:**
[IImage](../../com.aspose.slides/iimage) - Objekty bitmap.
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

Umožňuje přístup k poznámkovému snímku, přidání a odebrání. Pouze pro čtení [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Vrací:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

Vrací všechny komentáře ke snímku přidané konkrétním autorem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Autor komentářů, které se mají najít, nebo null pro vrácení všech komentářů. |

**Vrací:**
com.aspose.slides.IComment[] - Pole [IComment](../../com.aspose.slides/icomment).
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Uloží obsah snímku jako soubor SVG.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Cílový proud |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Uloží obsah snímku jako soubor SVG.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Cílový proud |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Možnosti generování SVG |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

Uloží obsah snímku jako soubor EMF.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Cílový proud |
### remove() {#remove--}
```
public abstract void remove()
```

Odstraní snímek z prezentace.
### reset() {#reset--}
```
public abstract void reset()
```

Obnoví pozici, velikost a formátování každého tvaru, který má prototyp na LayoutSlide.