---
title: ISlide
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een dia in een presentatie voor.
type: docs
url: /nl/com.aspose.slides/islide/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

Stelt een dia in een presentatie voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourneert de HeaderFooter-manager van de dia. |
| [getSlideNumber()](#getSlideNumber--) | Retourneert het nummer van de dia. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Retourneert het nummer van de dia. |
| [getHidden()](#getHidden--) | Bepaalt of de opgegeven dia verborgen is tijdens een diavoorstelling. |
| [setHidden(boolean value)](#setHidden-boolean-) | Bepaalt of de opgegeven dia verborgen is tijdens een diavoorstelling. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Retourneert een afbeeldingobject met aangepaste schaal. |
| [getImage()](#getImage--) | Retourneert een miniatuurafbeeldingobject (20% van de werkelijke grootte). |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Retourneert een afbeeldingobject met gespecificeerde grootte. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Retourneert een miniatuur-tiff-bitmapobject met opgegeven parameters. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Retourneert een miniatuur-bitmapobject. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Retourneert een miniatuur-bitmapobject met aangepaste schaal. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Retourneert een miniatuur-bitmapobject met gespecificeerde grootte. |
| [getLayoutSlide()](#getLayoutSlide--) | Retourneert of stelt de lay-outdia in voor de huidige dia. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Retourneert of stelt de lay-outdia in voor de huidige dia. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Staat toe toegang te krijgen tot de notitiedia, deze toe te voegen en te verwijderen. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Retourneert alle dia-commentaren die door een specifieke auteur zijn toegevoegd. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Slaat de inhoud van de dia op als een SVG-bestand. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Slaat de inhoud van de dia op als een SVG-bestand. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Slaat de inhoud van de dia op als een EMF-bestand. |
| [remove()](#remove--) | Verwijdert de dia uit de presentatie. |
| [reset()](#reset--) | Stelt positie, grootte en opmaak van elke vorm die een prototype heeft op LayoutSlide opnieuw in. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

Retourneert de HeaderFooter-manager van de dia. Alleen-lezen [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Retourneert:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

Retourneert het nummer van de dia. Index van de dia in de [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides)-collectie is altijd gelijk aan SlideNumber - 1. Lezen/schrijven int.

**Retourneert:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

Retourneert het nummer van de dia. Index van de dia in de [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides)-collectie is altijd gelijk aan SlideNumber - 1. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Bepaalt of de opgegeven dia verborgen is tijdens een diavoorstelling. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Bepaalt of de opgegeven dia verborgen is tijdens een diavoorstelling. Lezen/schrijven boolean.

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
| scaleX | float | De waarde waarmee deze miniatuur wordt geschaald in de x-as richting. |
| scaleY | float | De waarde waarmee deze miniatuur wordt geschaald in de y-as richting. |

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Afbeeldingsobject android.graphics.Bitmap
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Retourneert een miniatuur-afbeeldingsobject (20% van de werkelijke grootte).

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Afbeeldingsobject android.graphics.Bitmap
### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(Size imageSize)
```

Retourneert een afbeeldingobject met gespecificeerde grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Grootte van de afbeelding die moet worden gemaakt. |

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Bitmap-object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

Retourneert een miniatuur-tiff-bitmapobject met opgegeven parameters.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff-opties. |

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Afbeeldingsobject.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

Retourneert een miniatuur-bitmapobject.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-opties. |

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Bitmap-objecten.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Retourneert een miniatuur-bitmapobject met aangepaste schaal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-opties. |
| scaleX | float | De waarde waarmee deze miniatuur wordt geschaald in de x-as richting. |
| scaleY | float | De waarde waarmee deze miniatuur wordt geschaald in de y-as richting. |

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Bitmap-objecten.
### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(IRenderingOptions options, Size imageSize)
```

Retourneert een miniatuur-bitmapobject met gespecificeerde grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-opties. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Grootte van de afbeelding die moet worden gemaakt. |

**Retourneert:**
[IImage](../../com.aspose.slides/iimage) - Bitmap-objecten.
### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

Retourneert of stelt de lay-outdia in voor de huidige dia. Lezen/schrijven [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Retourneert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

Retourneert of stelt de lay-outdia in voor de huidige dia. Lezen/schrijven [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

Staat toe toegang te krijgen tot de notitiedia, deze toe te voegen en te verwijderen. Alleen-lezen [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Retourneert:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

Retourneert alle dia-commentaren die door een specifieke auteur zijn toegevoegd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Auteur van de te vinden commentaren of null om alle commentaren te retourneren. |

**Retourneert:**
com.aspose.slides.IComment[] - Array van [IComment](../../com.aspose.slides/icomment).
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Slaat de inhoud van de dia op als een SVG-bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Doelstream |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Slaat de inhoud van de dia op als een SVG-bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Doelstream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG-generatie-opties |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

Slaat de inhoud van de dia op als een EMF-bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Doelstream |
### remove() {#remove--}
```
public abstract void remove()
```

Verwijdert de dia uit de presentatie.

### reset() {#reset--}
```
public abstract void reset()
```

Stelt positie, grootte en opmaak van elke vorm die een prototype heeft op LayoutSlide opnieuw in.