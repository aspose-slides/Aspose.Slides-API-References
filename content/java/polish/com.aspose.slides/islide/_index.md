---
title: ISlide
second_title: Aspose.Slides dla Java – dokumentacja API
description: Reprezentuje slajd w prezentacji.
type: docs
url: /pl/com.aspose.slides/islide/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

Reprezentuje slajd w prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Zwraca menedżera HeaderFooter slajdu. |
| [getSlideNumber()](#getSlideNumber--) | Zwraca numer slajdu. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Zwraca numer slajdu. |
| [getHidden()](#getHidden--) | Określa, czy określony slajd jest ukryty podczas pokazu slajdów. |
| [setHidden(boolean value)](#setHidden-boolean-) | Określa, czy określony slajd jest ukryty podczas pokazu slajdów. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Zwraca obiekt obrazu ze skalowaniem niestandardowym. |
| [getImage()](#getImage--) | Zwraca obiekt Miniatury Image (20% rzeczywistego rozmiaru). |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | Zwraca obiekt obrazu o określonym rozmiarze. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Zwraca obiekt miniatury bitmapy tiff z określonymi parametrami. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Zwraca obiekt Miniatury Bitmap. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Zwraca obiekt Miniatury Bitmap ze skalowaniem niestandardowym. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Zwraca obiekt Miniatury Bitmap o określonym rozmiarze. |
| [getLayoutSlide()](#getLayoutSlide--) | Zwraca lub ustawia slajd układu dla bieżącego slajdu. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Zwraca lub ustawia slajd układu dla bieżącego slajdu. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Umożliwia dostęp do slajdu notatek, dodawanie i usuwanie go. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Zwraca wszystkie komentarze slajdu dodane przez konkretnego autora. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Zapisuje zawartość slajdu jako plik SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Zapisuje zawartość slajdu jako plik SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Zapisuje zawartość slajdu jako plik EMF. |
| [remove()](#remove--) | Usuwa slajd z prezentacji. |
| [reset()](#reset--) | Resetuje pozycję, rozmiar i formatowanie każdego kształtu, który ma prototyp na LayoutSlide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```


Zwraca menedżera HeaderFooter slajdu. Tylko do odczytu [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Zwraca:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```


Zwraca numer slajdu. Indeks slajdu w kolekcji [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) jest zawsze równy SlideNumber - 1. Do odczytu i zapisu int.

**Zwraca:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```


Zwraca numer slajdu. Indeks slajdu w kolekcji [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) jest zawsze równy SlideNumber - 1. Do odczytu i zapisu int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```


Określa, czy określony slajd jest ukryty podczas pokazu slajdów. Do odczytu i zapisu boolean.

**Zwraca:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```


Określa, czy określony slajd jest ukryty podczas pokazu slajdów. Do odczytu i zapisu boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```


Zwraca obiekt obrazu ze skalowaniem niestandardowym.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| scaleX | float | Wartość, o którą należy skalować tę Thumbnail w kierunku osi x. |
| scaleY | float | Wartość, o którą należy skalować tę Thumbnail w kierunku osi y. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Zwraca obiekt Miniatury Image (20% rzeczywistego rozmiaru).

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage
### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public abstract IImage getImage(Dimension imageSize)
```


Zwraca obiekt obrazu o określonym rozmiarze.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| imageSize | java.awt.Dimension | Rozmiar obrazu do utworzenia. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```


Zwraca obiekt miniatury bitmapy tiff z określonymi parametrami.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Opcje tiff. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```


Zwraca obiekt Miniatury Bitmap.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje renderowania. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```


Zwraca obiekt Miniatury Bitmap ze skalowaniem niestandardowym.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje renderowania. |
| scaleX | float | Wartość, o którą należy skalować tę Thumbnail w kierunku osi x. |
| scaleY | float | Wartość, o którą należy skalować tę Thumbnail w kierunku osi y. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage getImage(IRenderingOptions options, Dimension imageSize)
```


Zwraca obiekt Miniatury Bitmap o określonym rozmiarze.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje renderowania. |
| imageSize | java.awt.Dimension | Rozmiar obrazu do utworzenia. |

**Zwraca:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```


Zwraca lub ustawia slajd układu dla bieżącego slajdu. Do odczytu i zapisu [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Zwraca:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```


Zwraca lub ustawia slajd układu dla bieżącego slajdu. Do odczytu i zapisu [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```


Umożliwia dostęp do slajdu notatek, dodawanie i usuwanie go. Tylko do odczytu [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Zwraca:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```


Zwraca wszystkie komentarze slajdu dodane przez konkretnego autora.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Autor komentarzy do znalezienia lub null, aby zwrócić wszystkie komentarze. |

**Zwraca:**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```


Zapisuje zawartość slajdu jako plik SVG.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień docelowy |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```


Zapisuje zawartość slajdu jako plik SVG.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień docelowy |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opcje generowania SVG |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


Zapisuje zawartość slajdu jako plik EMF.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień docelowy |
### remove() {#remove--}
```
public abstract void remove()
```


Usuwa slajd z prezentacji.
### reset() {#reset--}
```
public abstract void reset()
```


Resetuje pozycję, rozmiar i formatowanie każdego kształtu, który ma prototyp na LayoutSlide.