---
title: ISlide
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een slide in een presentatie voor.
type: docs
url: /nl/com.aspose.slides/islide/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

Stelt een slide in een presentatie voor.
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourneert de HeaderFooter-beheerder van de slide. |
| [getSlideNumber()](#getSlideNumber--) | Retourneert het nummer van de slide. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Retourneert het nummer van de slide. |
| [getHidden()](#getHidden--) | Bepaalt of de opgegeven slide verborgen is tijdens een diavoorstelling. |
| [setHidden(boolean value)](#setHidden-boolean-) | Bepaalt of de opgegeven slide verborgen is tijdens een diavoorstelling. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Retourneert een afbeeldingobject met aangepaste schaal. |
| [getImage()](#getImage--) | Retourneert een miniatuurfoto-object (20% van de werkelijke grootte). |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | Retourneert een afbeeldingobject met opgegeven grootte. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Retourneert een miniatuur-tiff-bitmapobject met opgegeven parameters. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Retourneert een miniatuur-bitmapobject. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Retourneert een miniatuur-bitmapobject met aangepaste schaal. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Retourneert een miniatuur-bitmapobject met opgegeven grootte. |
| [getLayoutSlide()](#getLayoutSlide--) | Retourneert of stelt de layoutslide voor de huidige slide in. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Retourneert of stelt de layoutslide voor de huidige slide in. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Staat toe notitieslide te benaderen, toe te voegen en te verwijderen. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Retourneert alle slidecommentaren die door een specifieke auteur zijn toegevoegd. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Slaat de slide-inhoud op als een SVG-bestand. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Slaat de slide-inhoud op als een SVG-bestand. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Slaat de slide-inhoud op als een EMF-bestand. |
| [remove()](#remove--) | Verwijdert de slide uit de presentatie. |
| [reset()](#reset--) | Reset de positie, grootte en opmaak van elke vorm die een prototype heeft op LayoutSlide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```


Retourneert de HeaderFooter-beheerder van de slide. Alleen-lezen [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Retour:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```


Retourneert het nummer van de slide. Index van de slide in de [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides)-collectie is altijd gelijk aan SlideNumber - 1. Lezen/schrijven int.

**Retour:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```


Retourneert het nummer van de slide. Index van de slide in de [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides)-collectie is altijd gelijk aan SlideNumber - 1. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```


Bepaalt of de opgegeven slide verborgen is tijdens een diavoorstelling. Lezen/schrijven boolean.

**Retour:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```


Bepaalt of de opgegeven slide verborgen is tijdens een diavoorstelling. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```


Retourneert een afbeeldingobject met aangepaste schaal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scaleX | float | De waarde waarmee deze miniatuur in de x-richting wordt geschaald. |
| scaleY | float | De waarde waarmee deze miniatuur in de y-richting wordt geschaald. |

**Retour:**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Retourneert een miniatuurbeeldobject (20% van de werkelijke grootte).

**Retour:**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage
### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public abstract IImage getImage(Dimension imageSize)
```


Retourneert een afbeeldingobject met opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageSize | java.awt.Dimension | Grootte van de te maken afbeelding. |

**Retour:**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```


Retourneert een miniatuur-tiff-bitmapobject met opgegeven parameters.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff-opties. |

**Retour:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```


Retourneert een miniatuur-bitmapobject.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderopties. |

**Retour:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```


Retourneert een miniatuur-bitmapobject met aangepaste schaal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderopties. |
| scaleX | float | De waarde waarmee deze miniatuur in de x-richting wordt geschaald. |
| scaleY | float | De waarde waarmee deze miniatuur in de y-richting wordt geschaald. |

**Retour:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage getImage(IRenderingOptions options, Dimension imageSize)
```


Retourneert een miniatuur-bitmapobject met opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderopties. |
| imageSize | java.awt.Dimension | Grootte van de te maken afbeelding. |

**Retour:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```


Retourneert of stelt de layoutslide voor de huidige slide in. Lezen/schrijven [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Retour:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```


Retourneert of stelt de layoutslide voor de huidige slide in. Lezen/schrijven [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```


Staat toe notitieslide te benaderen, toe te voegen en te verwijderen. Alleen-lezen [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Retour:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```


Retourneert alle slidecommentaren die door een specifieke auteur zijn toegevoegd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Auteur van de te vinden commentaren of null om alle commentaren terug te geven. |

**Retour:**
com.aspose.slides.IComment[] - Array van [IComment](../../com.aspose.slides/icomment).
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```


Slaat de slide-inhoud op als een SVG-bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Doelstream |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```


Slaat de slide-inhoud op als een SVG-bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Doelstream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG-generatieopties |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


Slaat de slide-inhoud op als een EMF-bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Doelstream |
### remove() {#remove--}
```
public abstract void remove()
```


Verwijdert de slide uit de presentatie.
### reset() {#reset--}
```
public abstract void reset()
```


Reset de positie, grootte en opmaak van elke vorm die een prototype heeft op LayoutSlide.