---
title: LayoutSlide
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een lay-outslide voor.
type: docs
url: /nl/com.aspose.slides/layoutslide/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

Stelt een lay-out-slide voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourneert HeaderFooter-manager van de lay-out-slide. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Retourneert de placeholder-manager van de lay-out-slide. |
| [getMasterSlide()](#getMasterSlide--) | Retourneert of stelt de master-slide in voor een lay-out. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Retourneert of stelt de master-slide in voor een lay-out. |
| [remove()](#remove--) | Verwijdert lay-out uit presentatie. |
| [getThemeManager()](#getThemeManager--) | Retourneert de overschrijvende thema-manager. |
| [getLayoutType()](#getLayoutType--) | Retourneert de lay-out-type van deze lay-out-slide. |
| [getDependingSlides()](#getDependingSlides--) | Retourneert een array met alle dia's die afhankelijk zijn van deze lay-out-slide. |
| [hasDependingSlides()](#hasDependingSlides--) | Retourneert true als er minstens één dia bestaat die afhankelijk is van deze lay-out-slide. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specificeert of vormen op de master-slide al dan niet op dia's moeten worden weergegeven. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specificeert of vormen op de master-slide al dan niet op dia's moeten worden weergegeven. |
| [getDrawingGuides()](#getDrawingGuides--) | Retourneert een verzameling tekengidsen voor de lay-out-slide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


Retourneert HeaderFooter-manager van de lay-out-slide. Alleen-lezen [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Retour:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```


Retourneert de placeholder-manager van de lay-out-slide. Alleen-lezen [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Retour:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```


Retourneert of stelt de master-slide in voor een lay-out. Lezen/schrijven [IMasterSlide](../../com.aspose.slides/imasterslide).

**Retour:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```


Retourneert of stelt de master-slide in voor een lay-out. Lezen/schrijven [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### remove() {#remove--}
```
public final void remove()
```


Verwijdert lay-out uit presentatie.

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


Retourneert de overschrijvende thema-manager. Alleen-lezen [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Retour:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```


Retourneert de lay-out-type van deze lay-out-slide. Alleen-lezen [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Retour:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```


Retourneert een array met alle dia's die afhankelijk zijn van deze lay-out-slide.

**Retour:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```


Retourneert true als er minstens één dia bestaat die afhankelijk is van deze lay-out-slide. Alleen-lezen  boolean .

**Retour:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Specificeert of vormen op de master-slide al dan niet op dia's moeten worden weergegeven. Lezen/schrijven  boolean .

**Retour:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Specificeert of vormen op de master-slide al dan niet op dia's moeten worden weergegeven. Lezen/schrijven  boolean .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Retourneert een verzameling tekengidsen voor de lay-out-slide. Alleen-lezen [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Toevoegen van de nieuwe verticale tekengids links van het midden van de dia
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retour:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)