---
title: ILayoutSlide
second_title: Aspose.Slides för Java API-referens
description: Representerar en layout-bild.
type: docs
url: /sv/com.aspose.slides/ilayoutslide/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Representerar en layout-bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returnerar HeaderFooter-hanteraren för layout-bilden. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Returnerar platshållar-hanteraren för layout-bilden. |
| [getMasterSlide()](#getMasterSlide--) | Returnerar eller sätter master-slide för en layout. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Returnerar eller sätter master-slide för en layout. |
| [getLayoutType()](#getLayoutType--) | Returnerar layout-typen för den här layout-bilden. |
| [hasDependingSlides()](#hasDependingSlides--) | Returnerar true om det finns minst en bild som beror på den här layout-bilden. |
| [getDependingSlides()](#getDependingSlides--) | Returnerar en array med alla bilder som beror på den här layout-bilden. |
| [remove()](#remove--) | Tar bort layouten från presentationen. |
| [getDrawingGuides()](#getDrawingGuides--) | Returnerar en samling ritningsguider för layout-bilden. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Returnerar HeaderFooter-hanteraren för layout-bilden. Endast läsning [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Returnerar:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

Returnerar platshållar-hanteraren för layout-bilden. Endast läsning [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Returnerar:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```

Returnerar eller sätter master-slide för en layout. Läs/skriv [IMasterSlide](../../com.aspose.slides/imasterslide).

**Returnerar:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```

Returnerar eller sätter master-slide för en layout. Läs/skriv [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```

Returnerar layout-typen för den här layout-bilden. Endast läsning [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Returnerar:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Returnerar true om det finns minst en bild som beror på den här layout-bilden. Endast läsning boolean.

**Returnerar:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Returnerar en array med alla bilder som beror på den här layout-bilden.

**Returnerar:**
com.aspose.slides.ISlide[] - Array med alla bilder som beror på den här layout-bilden
### remove() {#remove--}
```
public abstract void remove()
```

Tar bort layouten från presentationen.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Returnerar en samling ritningsguider för layout-bilden. Endast läsning [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
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