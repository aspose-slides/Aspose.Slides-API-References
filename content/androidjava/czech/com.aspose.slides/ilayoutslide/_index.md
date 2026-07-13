---
title: ILayoutSlide
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Představuje rozvržení snímku.
type: docs
url: /cs/com.aspose.slides/ilayoutslide/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Představuje rozvržení snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Vrací HeaderFooter manager rozvržení snímku. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Vrací placeholder manager rozvržení snímku. |
| [getMasterSlide()](#getMasterSlide--) | Vrací nebo nastavuje hlavní snímek pro rozvržení. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Vrací nebo nastavuje hlavní snímek pro rozvržení. |
| [getLayoutType()](#getLayoutType--) | Vrací typ rozvržení tohoto rozvržení snímku. |
| [hasDependingSlides()](#hasDependingSlides--) | Vrací true, pokud existuje alespoň jeden snímek, který závisí na tomto rozvržení snímku. |
| [getDependingSlides()](#getDependingSlides--) | Vrací pole se všemi snímky, které závisí na tomto rozvržení snímku. |
| [remove()](#remove--) | Odstraňuje rozvržení z prezentace. |
| [getDrawingGuides()](#getDrawingGuides--) | Vrací kolekci kreslících vodítek pro rozvržení snímku. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Vrací HeaderFooter manager rozvržení snímku. Pouze ke čtení [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Vrací:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

Vrací placeholder manager rozvržení snímku. Pouze ke čtení [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Vrací:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```

Vrací nebo nastavuje hlavní snímek pro rozvržení. Čtení/zápis [IMasterSlide](../../com.aspose.slides/imasterslide).

**Vrací:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```

Vrací nebo nastavuje hlavní snímek pro rozvržení. Čtení/zápis [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```

Vrací typ rozvržení tohoto rozvržení snímku. Pouze ke čtení [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Vrací:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Vrací true, pokud existuje alespoň jeden snímek, který závisí na tomto rozvržení snímku. Pouze ke čtení boolean.

**Vrací:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Vrací pole se všemi snímky, které závisí na tomto rozvržení snímku.

**Vrací:**
com.aspose.slides.ISlide[] - Pole se všemi snímky, které závisí na tomto rozvržení snímku
### remove() {#remove--}
```
public abstract void remove()
```

Odstraňuje rozvržení z prezentace.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Vrací kolekci kreslících vodítek pro rozvržení snímku. Pouze ke čtení [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

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