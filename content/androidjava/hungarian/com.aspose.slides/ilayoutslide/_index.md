---
title: ILayoutSlide
second_title: Aspose.Slides for Android Java API hivatkozás
description: Egy elrendezés diát ábrázol.
type: docs
url: /hu/com.aspose.slides/ilayoutslide/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Egy elrendezés diát ábrázol.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a layout dia HeaderFooter manager-t. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Visszaadja a layout dia placeholder manager-t. |
| [getMasterSlide()](#getMasterSlide--) | Visszaadja vagy beállítja a master slide-t egy layouthoz. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Visszaadja vagy beállítja a master slide-t egy layouthoz. |
| [getLayoutType()](#getLayoutType--) | Visszaadja ennek a layout diáknak a layout típust. |
| [hasDependingSlides()](#hasDependingSlides--) | Visszaadja az igaz értéket, ha létezik legalább egy dia, amely függ ettől a layout diáktól. |
| [getDependingSlides()](#getDependingSlides--) | Visszaad egy tömböt az összes diával, amelyek függnek ettől a layout diáktól. |
| [remove()](#remove--) | Eltávolítja a layoutot a prezentációból. |
| [getDrawingGuides()](#getDrawingGuides--) | Visszaadja a layout dia rajz útmutatóinak gyűjteményét. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Visszaadja a layout dia HeaderFooter manager-t. Csak olvasható [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Visszatér:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

Visszaadja a layout dia placeholder manager-t. Csak olvasható [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Visszatér:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```

Visszaadja vagy beállítja a master slide-t egy layouthoz. Olvasás/írás [IMasterSlide](../../com.aspose.slides/imasterslide).

**Visszatér:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```

Visszaadja vagy beállítja a master slide-t egy layouthoz. Olvasás/írás [IMasterSlide](../../com.aspose.slides/imasterslide).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```

Visszaadja ennek a layout diáknak a layout típust. Csak olvasható [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Visszatér:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Visszaadja az igaz értéket, ha létezik legalább egy dia, amely függ ettől a layout diáktól. Csak olvasható boolean.

**Visszatér:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Visszaad egy tömböt az összes diával, amelyek függnek ettől a layout diáktól.

**Visszatér:**
com.aspose.slides.ISlide[] - Tömb az összes diával, amely függ ettől a layout diáktól
### remove() {#remove--}
```
public abstract void remove()
```

Eltávolítja a layoutot a prezentációból.
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Visszaadja a layout dia rajz útmutatóinak gyűjteményét. Csak olvasható [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Új függőleges rajz útmutató hozzáadása a diaközép bal oldalához
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)