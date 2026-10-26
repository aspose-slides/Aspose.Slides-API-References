---
title: ILayoutSlide
second_title: Aspose.Slides Java API referencia
description: Egy layout slide-ot reprezentál.
type: docs
url: /hu/com.aspose.slides/ilayoutslide/
---
**Összes megvalósított interfész:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Egy layout slide-ot reprezentál.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a layout slide HeaderFooter manager-jét. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Visszaadja a layout slide placeholder manager-jét. |
| [getMasterSlide()](#getMasterSlide--) | Visszaadja vagy beállítja a layout master slide-t. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Visszaadja vagy beállítja a layout master slide-t. |
| [getLayoutType()](#getLayoutType--) | Visszaadja ennek a layout slide-nak a layout type-ját. |
| [hasDependingSlides()](#hasDependingSlides--) | Igaz értéket ad vissza, ha létezik legalább egy diа, amely függ ettől a layout slide-tól. |
| [getDependingSlides()](#getDependingSlides--) | Visszaad egy tömböt az összes slide-dal, amely függ ettől a layout slide-tól. |
| [remove()](#remove--) | Eltávolítja a layout-ot a prezentációból. |
| [getDrawingGuides()](#getDrawingGuides--) | Visszaad egy gyűjteményt a layout slide rajz útmutatóiból. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


Visszaadja a layout slide HeaderFooter manager-jét. Csak olvasható [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Visszatér:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```


Visszaadja a layout slide placeholder manager-jét. Csak olvasható [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Visszatér:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```


Visszaadja vagy beállítja a layout master slide-t. Olvasás/írás [IMasterSlide](../../com.aspose.slides/imasterslide).

**Visszatér:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```


Visszaadja vagy beállítja a layout master slide-t. Olvasás/írás [IMasterSlide](../../com.aspose.slides/imasterslide).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```


Visszaadja ennek a layout slide-nak a layout type-ját. Csak olvasható [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Visszatér:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


Igaz értéket ad vissza, ha létezik legalább egy diа, amely függ ettől a layout slide-tól. Csak olvasható boolean.

**Visszatér:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```


Visszaad egy tömböt az összes slide-dal, amely függ ettől a layout slide-tól.

**Visszatér:**
com.aspose.slides.ISlide[] - Tömb az összes slide-dal, amely függ ettől a layout slide-tól
### remove() {#remove--}
```
public abstract void remove()
```


Eltávolítja a layout-ot a prezentációból.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Visszaad egy gyűjteményt a layout slide rajz útmutatóiból. Csak olvasható [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Az új függőleges rajzútmutató hozzáadása a dia középpontjának bal oldalához
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)