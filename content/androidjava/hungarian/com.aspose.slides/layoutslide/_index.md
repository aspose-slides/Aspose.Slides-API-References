---
title: LayoutSlide
second_title: Aspose.Slides Android számára a Java API hivatkozásával
description: Elrendezési diát reprezentál.
type: docs
url: /hu/com.aspose.slides/layoutslide/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Minden megvalósított interfész:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

Egy elrendezési diát ábrázol.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a layout dia HeaderFooter-kezelőjét. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Visszaadja a layout dia placeholder-kezelőjét. |
| [getMasterSlide()](#getMasterSlide--) | Visszaadja vagy beállítja a master slide-ot a layouthoz. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Visszaadja vagy beállítja a master slide-ot a layouthoz. |
| [remove()](#remove--) | Eltávolítja a layoutot a prezentációból. |
| [getThemeManager()](#getThemeManager--) | Visszaadja a felülíró téma-kezelőt. |
| [getLayoutType()](#getLayoutType--) | Visszaadja ennek a layout diáknak a layout típusát. |
| [getDependingSlides()](#getDependingSlides--) | Visszaad egy tömböt az összes diával, amely függ ettől a layout diáktól. |
| [hasDependingSlides()](#hasDependingSlides--) | Igaz értéket ad vissza, ha létezik legalább egy dia, amely függ ettől a layout diáktól. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Megadja, hogy a master slide alakjai megjelenjenek-e a diákon vagy sem. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Megadja, hogy a master slide alakjai megjelenjenek-e a diákon vagy sem. |
| [getDrawingGuides()](#getDrawingGuides--) | Visszaad egy gyűjteményt a layout dia rajzolási segédleteiről. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


Visszaadja a layout dia HeaderFooter-kezelőjét. Csak olvasható [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Visszaad:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```


Visszaadja a layout dia placeholder-kezelőjét. Csak olvasható [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Visszaad:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```


Visszaadja vagy beállítja a master slide-ot egy layouthoz. Olvasás/írás [IMasterSlide](../../com.aspose.slides/imasterslide).

**Visszaad:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```


Visszaadja vagy beállítja a master slide-ot egy layouthoz. Olvasás/írás [IMasterSlide](../../com.aspose.slides/imasterslide).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### remove() {#remove--}
```
public final void remove()
```


Eltávolítja a layoutot a prezentációból.
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


Visszaadja a felülíró téma-kezelőt. Csak olvasható [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Visszaad:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```


Visszaadja ennek a layout diáknak a layout típusát. Csak olvasható [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Visszaad:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```


Visszaad egy tömböt az összes diával, amely függ ettől a layout diáktól.

**Visszaad:**
com.aspose.slides.ISlide[] - A [ISlide](../../com.aspose.slides/islide) tömbje
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```


Igaz értéket ad vissza, ha létezik legalább egy dia, amely függ ettől a layout diáktól. Csak olvasható  boolean .

**Visszaad:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Megadja, hogy a master slide alakjai megjelenjenek-e a diákon vagy sem. Olvasás/írás  boolean .

**Visszaad:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Megadja, hogy a master slide alakjai megjelenjenek-e a diákon vagy sem. Olvasás/írás  boolean .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Visszaad egy gyűjteményt a layout dia rajzolási segédleteiről. Csak olvasható [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Új függőleges rajzsegédlet hozzáadása a dia középpontja bal oldalához
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszaad:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)