---
title: ILayoutSlide
second_title: Aspose.Slides dla Androida - odniesienie do API Java
description: Reprezentuje slajd układu.
type: docs
url: /pl/com.aspose.slides/ilayoutslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Reprezentuje slajd układu.
## Metody

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Zwraca menedżera HeaderFooter układu slajdu. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Zwraca menedżera placeholder układu slajdu. |
| [getMasterSlide()](#getMasterSlide--) | Zwraca lub ustawia master slide dla układu. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Zwraca lub ustawia master slide dla układu. |
| [getLayoutType()](#getLayoutType--) | Zwraca typ układu tego slajdu układu. |
| [hasDependingSlides()](#hasDependingSlides--) | Zwraca true, jeśli istnieje co najmniej jeden slajd zależny od tego slajdu układu. |
| [getDependingSlides()](#getDependingSlides--) | Zwraca tablicę ze wszystkimi slajdami, które zależą od tego slajdu układu. |
| [remove()](#remove--) | Usuwa układ z prezentacji. |
| [getDrawingGuides()](#getDrawingGuides--) | Zwraca kolekcję rysunkowych przewodników dla slajdu układu. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Zwraca menedżera HeaderFooter układu slajdu. Tylko do odczytu [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Zwraca:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

Zwraca menedżera placeholder układu slajdu. Tylko do odczytu [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Zwraca:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```

Zwraca lub ustawia master slide dla układu. Odczyt/zapis [IMasterSlide](../../com.aspose.slides/imasterslide).

**Zwraca:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```

Zwraca lub ustawia master slide dla układu. Odczyt/zapis [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```

Zwraca typ układu tego slajdu układu. Tylko do odczytu [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Zwraca:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Zwraca true, jeśli istnieje co najmniej jeden slajd zależny od tego slajdu układu. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Zwraca tablicę ze wszystkimi slajdami, które zależą od tego slajdu układu.

**Zwraca:**
com.aspose.slides.ISlide[] - Tablica ze wszystkimi slajdami, które zależą od tego slajdu układu
### remove() {#remove--}
```
public abstract void remove()
```

Usuwa układ z prezentacji.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Zwraca kolekcję rysunkowych przewodników dla slajdu układu. Tylko do odczytu [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Dodawanie nowego pionowego przewodnika rysowania po lewej stronie środka slajdu
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)