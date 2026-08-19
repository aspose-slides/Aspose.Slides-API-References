---
title: LayoutSlide
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een lay-outdia voor.
type: docs
url: /nl/com.aspose.slides/layoutslide/
---
**Overerving:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

Stelt een lay-outdia voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourneert de HeaderFooter-beheerder van de lay-outdia. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Retourneert de placeholder manager van de lay-outdia. |
| [getMasterSlide()](#getMasterSlide--) | Retourneert of stelt de master slide in voor een lay-out. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Retourneert of stelt de master slide in voor een lay-out. |
| [remove()](#remove--) | Verwijdert de lay-out uit de presentatie. |
| [getThemeManager()](#getThemeManager--) | Retourneert de overriding theme manager. |
| [getLayoutType()](#getLayoutType--) | Retourneert het layouttype van deze lay-outdia. |
| [getDependingSlides()](#getDependingSlides--) | Retourneert een array met alle dia's die afhankelijk zijn van deze lay-outdia. |
| [hasDependingSlides()](#hasDependingSlides--) | Retourneert true als er minstens één dia bestaat die afhankelijk is van deze lay-outdia. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specificeert of vormen op de master slide moeten worden weergegeven op dia's of niet. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specificeert of vormen op de master slide moeten worden weergegeven op dia's of niet. |
| [getDrawingGuides()](#getDrawingGuides--) | Retourneert een collectie van tekenrichtlijnen voor de lay-outdia. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Retourneert de HeaderFooter-beheerder van de lay-outdia. Alleen-lezen [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Retourneert:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```

Retourneert de placeholder manager van de lay-outdia. Alleen-lezen [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Retourneert:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```

Retourneert of stelt de master slide in voor een lay-out. Lezen/schrijven [IMasterSlide](../../com.aspose.slides/imasterslide).

**Retourneert:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```

Retourneert of stelt de master slide in voor een lay-out. Lezen/schrijven [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### remove() {#remove--}
```
public final void remove()
```

Verwijdert de lay-out uit de presentatie.

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Retourneert de overriding theme manager. Alleen-lezen [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Retourneert:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```

Retourneert het layouttype van deze lay-outdia. Alleen-lezen [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Retourneert:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Retourneert een array met alle dia's die afhankelijk zijn van deze lay-outdia.

**Retourneert:**
com.aspose.slides.ISlide[] - Array van [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Retourneert true als er minstens één dia bestaat die afhankelijk is van deze lay-outdia. Alleen-lezen boolean.

**Retourneert:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Specificeert of vormen op de master slide moeten worden weergegeven op dia's of niet. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Specificeert of vormen op de master slide moeten worden weergegeven op dia's of niet. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Retourneert een collectie van tekenrichtlijnen voor de lay-outdia. Alleen-lezen [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Voegt de nieuwe verticale tekenrichtlijn toe links van het midden van de dia
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)