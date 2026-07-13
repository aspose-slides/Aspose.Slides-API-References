---
title: LayoutSlide
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje rozvržení snímku.
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

Reprezentuje rozvržení snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Vrací správce HeaderFooter rozvržení snímku. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Vrací správce placeholder rozvržení snímku. |
| [getMasterSlide()](#getMasterSlide--) | Vrací nebo nastavuje hlavní snímek pro rozvržení. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Vrací nebo nastavuje hlavní snímek pro rozvržení. |
| [remove()](#remove--) | Odstraňuje rozvržení z prezentace. |
| [getThemeManager()](#getThemeManager--) | Vrací přepisující správce motivu. |
| [getLayoutType()](#getLayoutType--) | Vrací typ rozvržení tohoto rozvržení snímku. |
| [getDependingSlides()](#getDependingSlides--) | Vrací pole se všemi snímky, které závisejí na tomto rozvržení snímku. |
| [hasDependingSlides()](#hasDependingSlides--) | Vrací true, pokud existuje alespoň jeden snímek, který závisí na tomto rozvržení snímku. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích, či nikoli. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích, či nikoli. |
| [getDrawingGuides()](#getDrawingGuides--) | Vrací kolekci kreslicích vodítek pro rozvržení snímku. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Vrací správce HeaderFooter rozvržení snímku. Pouze pro čtení [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Vrací:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```

Vrací správce placeholder rozvržení snímku. Pouze pro čtení [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

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

Odstraňuje rozvržení z prezentace.
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

Vrací typ rozvržení tohoto rozvržení snímku. Pouze pro čtení [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Vrací:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Vrací pole se všemi snímky, které závisejí na tomto rozvržení snímku.

**Vrací:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Vrací true, pokud existuje alespoň jeden snímek, který závisí na tomto rozvržení snímku. Pouze pro čtení boolean .

**Vrací:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích, či nikoli. Čtení/Zápis boolean .

**Vrací:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích, či nikoli. Čtení/Zápis boolean .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Vrací kolekci kreslicích vodítek pro rozvržení snímku. Pouze pro čtení [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Přidání nového svislého kreslicího vodítka vlevo od středu snímku
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)