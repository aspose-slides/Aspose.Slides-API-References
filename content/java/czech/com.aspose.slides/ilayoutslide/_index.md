---
title: ILayoutSlide
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje rozložení snímku.
type: docs
url: /cs/com.aspose.slides/ilayoutslide/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Reprezentuje rozložení snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Vrací HeaderFooter manager rozložení snímku. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Vrací manager placeholder rozložení snímku. |
| [getMasterSlide()](#getMasterSlide--) | Vrací nebo nastavuje master slide pro rozložení. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Vrací nebo nastavuje master slide pro rozložení. |
| [getLayoutType()](#getLayoutType--) | Vrací typ rozložení tohoto rozložení snímku. |
| [hasDependingSlides()](#hasDependingSlides--) | Vrací true, pokud existuje alespoň jeden snímek, který závisí na tomto rozložení snímku. |
| [getDependingSlides()](#getDependingSlides--) | Vrací pole se všemi snímky, které závisí na tomto rozložení snímku. |
| [remove()](#remove--) | Odstraní rozložení z prezentace. |
| [getDrawingGuides()](#getDrawingGuides--) | Vrací kolekci kreslících vodítek pro rozložení snímku. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Vrací HeaderFooter manager rozložení snímku. Pouze pro čtení [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Vrací:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

Vrací manager placeholder rozložení snímku. Pouze pro čtení [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Vrací:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```

Vrací nebo nastavuje master slide pro rozložení. Čtení/Zápis [IMasterSlide](../../com.aspose.slides/imasterslide).

**Vrací:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```

Vrací nebo nastavuje master slide pro rozložení. Čtení/Zápis [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```

Vrací typ rozložení tohoto rozložení snímku. Pouze pro čtení [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Vrací:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Vrací true, pokud existuje alespoň jeden snímek, který závisí na tomto rozložení snímku. Pouze pro čtení boolean.

**Vrací:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Vrací pole se všemi snímky, které závisí na tomto rozložení snímku.

**Vrací:**
com.aspose.slides.ISlide[] - Pole se všemi snímky, které závisí na tomto rozložení snímku
### remove() {#remove--}
```
public abstract void remove()
```

Odstraní rozložení z prezentace.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Vrací kolekci kreslících vodítek pro rozložení snímku. Pouze pro čtení [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Přidání nového svislého kreslícího vodítka vlevo od středu snímku
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)