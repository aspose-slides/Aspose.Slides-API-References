---
title: LayoutSlide
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en layout-bild.
type: docs
url: /sv/com.aspose.slides/layoutslide/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**All Implemented Interfaces:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

Representerar en layout-bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returnerar HeaderFooter-hanteraren för layout-bilden. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Returnerar platshållar-hanteraren för layout-bilden. |
| [getMasterSlide()](#getMasterSlide--) | Returnerar eller anger master-bilden för en layout. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Returnerar eller anger master-bilden för en layout. |
| [remove()](#remove--) | Tar bort layouten från presentationen. |
| [getThemeManager()](#getThemeManager--) | Returnerar den överskrivande temahanteraren. |
| [getLayoutType()](#getLayoutType--) | Returnerar layout-typ för denna layout-bild. |
| [getDependingSlides()](#getDependingSlides--) | Returnerar en array med alla bilder som är beroende av denna layout-bild. |
| [hasDependingSlides()](#hasDependingSlides--) | Returnerar true om det finns minst en bild som är beroende av denna layout-bild. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Anger om former på master-bilden ska visas på bilder eller inte. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Anger om former på master-bilden ska visas på bilder eller inte. |
| [getDrawingGuides()](#getDrawingGuides--) | Returnerar en samling av ritningsguider för layout-bilden. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


Returnerar HeaderFooter-hanteraren för layout-bilden. Skrivskyddad [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Returnerar:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```


Returnerar platshållar-hanteraren för layout-bilden. Skrivskyddad [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Returnerar:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```


Returnerar eller anger master-bilden för en layout. Läs/skriv [IMasterSlide](../../com.aspose.slides/imasterslide).

**Returnerar:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```


Returnerar eller anger master-bilden för en layout. Läs/skriv [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### remove() {#remove--}
```
public final void remove()
```


Tar bort layouten från presentationen.

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


Returnerar den överskrivande temahanteraren. Skrivskyddad [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Returnerar:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```


Returnerar layout-typ för denna layout-bild. Skrivskyddad [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Returnerar:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```


Returnerar en array med alla bilder som är beroende av denna layout-bild.

**Returnerar:**
com.aspose.slides.ISlide[] - Array av [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```


Returnerar true om det finns minst en bild som är beroende av denna layout-bild. Skrivskyddad boolean .

**Returnerar:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Anger om former på master-bilden ska visas på bilder eller inte. Läs/skriv boolean .

**Returnerar:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Anger om former på master-bilden ska visas på bilder eller inte. Läs/skriv boolean .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Returnerar en samling av ritningsguider för layout-bilden. Skrivskyddad [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Lägger till den nya vertikala ritningsguiden till vänster om bildens centrum
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)