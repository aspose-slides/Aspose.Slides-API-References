---
title: LayoutSlide
second_title: Aspose.Slides Java API-referencia
description: Egy elrendezési diát képvisel.
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

Egy elrendezési diát képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a HeaderFooter kezelőt az elrendezés dián. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Visszaadja a placeholder kezelőt az elrendezés dián. |
| [getMasterSlide()](#getMasterSlide--) | Visszaadja vagy beállítja a mester diát egy elrendezéshez. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Visszaadja vagy beállítja a mester diát egy elrendezéshez. |
| [remove()](#remove--) | Eltávolítja az elrendezést a prezentációból. |
| [getThemeManager()](#getThemeManager--) | Visszaadja a felülíró téma kezelőt. |
| [getLayoutType()](#getLayoutType--) | Visszaadja az elrendezés diájának típusát. |
| [getDependingSlides()](#getDependingSlides--) | Visszaad egy tömböt az összes diával, amely ezt az elrendezés diát használja. |
| [hasDependingSlides()](#hasDependingSlides--) | Igazat ad, ha létezik legalább egy dia, amely ezt az elrendezés diát használja. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Megadja, hogy a mester dián lévő alakzatok megjelenjenek-e a diákon vagy sem. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Megadja, hogy a mester dián lévő alakzatok megjelenjenek-e a diákon vagy sem. |
| [getDrawingGuides()](#getDrawingGuides--) | Visszaad egy gyűjteményt a rajzolási segédvonalakról az elrendezés dián. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


Visszaadja a HeaderFooter kezelőt az elrendezés dián. Csak olvasható [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Visszaad:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```


Visszaadja a placeholder kezelőt az elrendezés dián. Csak olvasható [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Visszaad:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```


Visszaadja vagy beállítja a mester diát egy elrendezéshez. Olvasás/írás [IMasterSlide](../../com.aspose.slides/imasterslide).

**Visszaad:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```


Visszaadja vagy beállítja a mester diát egy elrendezéshez. Olvasás/írás [IMasterSlide](../../com.aspose.slides/imasterslide).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### remove() {#remove--}
```
public final void remove()
```


Eltávolítja az elrendezést a prezentációból.

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


Visszaadja a felülíró téma kezelőt. Csak olvasható [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Visszaad:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```


Visszaadja az elrendezés diájának típusát. Csak olvasható [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Visszaad:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```


Visszaad egy tömböt az összes diával, amely ezt az elrendezés diát használja.

**Visszaad:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```


Igazat ad, ha létezik legalább egy dia, amely ezt az elrendezés diát használja. Csak olvasható boolean .

**Visszaad:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Megadja, hogy a mester dián lévő alakzatok megjelenjenek-e a diákon vagy sem. Olvasás/írás boolean .

**Visszaad:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Megadja, hogy a mester dián lévő alakzatok megjelenjenek-e a diákon vagy sem. Olvasás/írás boolean .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Visszaad egy gyűjteményt a rajzolási segédvonalakról az elrendezés dián. Csak olvasható [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Az új függőleges rajzsegédvonal hozzáadása a dia középpontjának bal oldalához
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszaad:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)