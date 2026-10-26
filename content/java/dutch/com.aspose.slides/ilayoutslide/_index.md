---
title: ILayoutSlide
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een layout-dia voor.
type: docs
url: /nl/com.aspose.slides/ilayoutslide/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Stelt een layout-dia voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourneert HeaderFooter-manager van de layout-dia. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Retourneert de placeholder-manager van de layout-dia. |
| [getMasterSlide()](#getMasterSlide--) | Retourneert of stelt de master-slide in voor een layout. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Retourneert of stelt de master-slide in voor een layout. |
| [getLayoutType()](#getLayoutType--) | Retourneert layout-type van deze layout-dia. |
| [hasDependingSlides()](#hasDependingSlides--) | Retourneert true als er ten minste één dia bestaat die afhankelijk is van deze layout-dia. |
| [getDependingSlides()](#getDependingSlides--) | Retourneert een array met alle dia’s die afhankelijk zijn van deze layout-dia. |
| [remove()](#remove--) | Verwijdert layout uit de presentatie. |
| [getDrawingGuides()](#getDrawingGuides--) | Retourneert een collectie teken-gidsen voor de layout-dia. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


Retourneert HeaderFooter-manager van de layout-dia. Alleen-lezen [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Retourneert:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```


Retourneert de placeholder-manager van de layout-dia. Alleen-lezen [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Retourneert:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```


Retourneert of stelt de master-slide in voor een layout. Lezen/Schrijven [IMasterSlide](../../com.aspose.slides/imasterslide).

**Retourneert:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```


Retourneert of stelt de master-slide in voor een layout. Lezen/Schrijven [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```


Retourneert layout-type van deze layout-dia. Alleen-lezen [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Retourneert:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


Retourneert true als er ten minste één dia bestaat die afhankelijk is van deze layout-dia. Alleen-lezen boolean.

**Retourneert:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```


Retourneert een array met alle dia’s die afhankelijk zijn van deze layout-dia.

**Retourneert:**
com.aspose.slides.ISlide[] - Array met alle dia’s die afhankelijk zijn van deze layout-dia
### remove() {#remove--}
```
public abstract void remove()
```


Verwijdert layout uit de presentatie.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Retourneert een collectie teken-gidsen voor de layout-dia. Alleen-lezen [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Toevoegen van de nieuwe verticale teken-gids links van het midden van de dia
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)