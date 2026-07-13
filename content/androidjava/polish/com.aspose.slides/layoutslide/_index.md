---
title: LayoutSlide
second_title: Aspose.Slides dla Androida – referencja Java API
description: Reprezentuje slajd układu.
type: docs
url: /pl/com.aspose.slides/layoutslide/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

Reprezentuje slajd układu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Zwraca menedżera HeaderFooter slajdu układu. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Zwraca menedżera placeholderów slajdu układu. |
| [getMasterSlide()](#getMasterSlide--) | Zwraca lub ustawia slajd główny dla układu. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Zwraca lub ustawia slajd główny dla układu. |
| [remove()](#remove--) | Usuwa układ z prezentacji. |
| [getThemeManager()](#getThemeManager--) | Zwraca menedżera nadpisującego motywu. |
| [getLayoutType()](#getLayoutType--) | Zwraca typ układu tego slajdu układu. |
| [getDependingSlides()](#getDependingSlides--) | Zwraca tablicę ze wszystkimi slajdami, które zależą od tego slajdu układu. |
| [hasDependingSlides()](#hasDependingSlides--) | Zwraca true, jeśli istnieje przynajmniej jeden slajd zależący od tego slajdu układu. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Określa, czy kształty na slajdzie głównym mają być wyświetlane na slajdach, czy nie. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Określa, czy kształty na slajdzie głównym mają być wyświetlane na slajdach, czy nie. |
| [getDrawingGuides()](#getDrawingGuides--) | Zwraca kolekcję przewodników rysowania dla slajdu układu. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


Zwraca menedżera HeaderFooter slajdu układu. Tylko do odczytu [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Zwraca:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```


Zwraca menedżera placeholderów slajdu układu. Tylko do odczytu [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Zwraca:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```


Zwraca lub ustawia slajd główny dla układu. Odczyt/zapis [IMasterSlide](../../com.aspose.slides/imasterslide).

**Zwraca:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```


Zwraca lub ustawia slajd główny dla układu. Odczyt/zapis [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### remove() {#remove--}
```
public final void remove()
```


Usuwa układ z prezentacji.

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


Zwraca menedżera nadpisującego motywu. Tylko do odczytu [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Zwraca:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```


Zwraca typ układu tego slajdu układu. Tylko do odczytu [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Zwraca:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```


Zwraca tablicę ze wszystkimi slajdami, które zależą od tego slajdu układu.

**Zwraca:**
com.aspose.slides.ISlide[] - Tablica [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```


Zwraca true, jeśli istnieje przynajmniej jeden slajd zależący od tego slajdu układu. Tylko do odczytu boolean .

**Zwraca:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Określa, czy kształty na slajdzie głównym mają być wyświetlane na slajdach, czy nie. Odczyt/zapis boolean .

**Zwraca:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Określa, czy kształty na slajdzie głównym mają być wyświetlane na slajdach, czy nie. Odczyt/zapis boolean .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Zwraca kolekcję przewodników rysowania dla slajdu układu. Tylko do odczytu [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Dodawanie nowej pionowej linii prowadzącej po lewej stronie środka slajdu
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)