---
title: LayoutSlide
second_title: Aspose.Slides pro Java - reference API
description: Reprezentuje snímek rozvržení.
type: docs
url: /cs/com.aspose.slides/layoutslide/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Všechny implementované rozhraní:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

Reprezentuje snímek rozvržení.
## Metody

| Metoda | Popis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Vrací správce HeaderFooter tohoto snímku rozvržení. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Vrací správce zástupného symbolu tohoto snímku rozvržení. |
| [getMasterSlide()](#getMasterSlide--) | Vrací nebo nastavuje hlavní snímek pro rozvržení. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Vrací nebo nastavuje hlavní snímek pro rozvržení. |
| [remove()](#remove--) | Odstraní rozvržení z prezentace. |
| [getThemeManager()](#getThemeManager--) | Vrací přepisující správce motivu. |
| [getLayoutType()](#getLayoutType--) | Vrací typ rozvržení tohoto snímku. |
| [getDependingSlides()](#getDependingSlides--) | Vrací pole se všemi snímky, které jsou závislé na tomto snímku rozvržení. |
| [hasDependingSlides()](#hasDependingSlides--) | Vrací pravdu, pokud existuje alespoň jeden snímek závislý na tomto snímku rozvržení. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích, nebo ne. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích, nebo ne. |
| [getDrawingGuides()](#getDrawingGuides--) | Vrací sbírku kreslicích vodítek pro snímek rozvržení. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Vrací správce HeaderFooter tohoto snímku rozvržení. Pouze pro čtení [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Vrací:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```

Vrací správce zástupného symbolu tohoto snímku rozvržení. Pouze pro čtení [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Vrací:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```

Vrací nebo nastavuje hlavní snímek pro rozvržení. Čtení/Zápis [IMasterSlide](../../com.aspose.slides/imasterslide).

**Vrací:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```

Vrací nebo nastavuje hlavní snímek pro rozvržení. Čtení/Zápis [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### remove() {#remove--}
```
public final void remove()
```

Odstraní rozvržení z prezentace.
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Vrací přepisující správce motivu. Pouze pro čtení [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Vrací:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```

Vrací typ rozvržení tohoto snímku. Pouze pro čtení [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Vrací:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Vrací pole se všemi snímky, které jsou závislé na tomto snímku rozvržení.

**Vrací:**
com.aspose.slides.ISlide[] - Pole [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Vrací pravdu, pokud existuje alespoň jeden snímek závislý na tomto snímku rozvržení. Pouze pro čtení boolean .

**Vrací:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích, nebo ne. Čtení/Zápis boolean .

**Vrací:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích, nebo ne. Čtení/Zápis boolean .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Vrací sbírku kreslicích vodítek pro snímek rozvržení. Pouze pro čtení [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Přidání nového vertikálního kreslicího vodítka vlevo od středu snímku
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)