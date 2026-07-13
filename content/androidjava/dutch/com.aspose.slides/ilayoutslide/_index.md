---
title: ILayoutSlide
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een layoutdia voor.
type: docs
url: /nl/com.aspose.slides/ilayoutslide/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Stelt een layoutdia voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourneert de HeaderFooter manager van de layoutdia. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Retourneert de placeholder manager van de layoutdia. |
| [getMasterSlide()](#getMasterSlide--) | Retourneert of stelt de master slide in voor een layout. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Retourneert of stelt de master slide in voor een layout. |
| [getLayoutType()](#getLayoutType--) | Retourneert layouttype van deze layoutdia. |
| [hasDependingSlides()](#hasDependingSlides--) | Retourneert true als er ten minste één dia bestaat die afhankelijk is van deze layoutdia. |
| [getDependingSlides()](#getDependingSlides--) | Retourneert een array met alle dia's die afhankelijk zijn van deze layoutdia. |
| [remove()](#remove--) | Verwijdert de layout uit de presentatie. |
| [getDrawingGuides()](#getDrawingGuides--) | Retourneert een collectie tekenrichtlijnen voor de layoutdia. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


Retourneert HeaderFooter manager van de layoutdia. Alleen-lezen [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Returns:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```


Retourneert de placeholder manager van de layoutdia. Alleen-lezen [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Returns:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```


Retourneert of stelt de master slide in voor een layout. Lees/schrijf [IMasterSlide](../../com.aspose.slides/imasterslide).

**Returns:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```


Retourneert of stelt de master slide in voor een layout. Lees/schrijf [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```


Retourneert layouttype van deze layoutdia. Alleen-lezen [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Returns:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


Retourneert true als er ten minste één dia bestaat die afhankelijk is van deze layoutdia. Alleen-lezen boolean.

**Returns:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```


Retourneert een array met alle dia's die afhankelijk zijn van deze layoutdia.

**Returns:**
com.aspose.slides.ISlide[] - Array met alle dia's die afhankelijk zijn van deze layoutdia
### remove() {#remove--}
```
public abstract void remove()
```


Verwijdert de layout uit de presentatie.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Retourneert een collectie tekenrichtlijnen voor de layoutdia. Alleen-lezen [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // De nieuwe verticale tekenrichtlijn toevoegen links van het midden van de dia
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)