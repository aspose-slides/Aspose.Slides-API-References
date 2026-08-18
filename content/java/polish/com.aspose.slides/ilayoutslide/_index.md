---
title: ILayoutSlide
second_title: Odwołanie API Aspose.Slides dla Javy
description: Reprezentuje slajd układu.
type: docs
url: /pl/com.aspose.slides/ilayoutslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Represents a layout slide.
## Metody

| Metoda | Opis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returns HeaderFooter manager of the layout slide. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Returns the placeholder manager of the layout slide. |
| [getMasterSlide()](#getMasterSlide--) | Returns or sets the master slide for a layout. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Returns or sets the master slide for a layout. |
| [getLayoutType()](#getLayoutType--) | Returns layout type of this layout slide. |
| [hasDependingSlides()](#hasDependingSlides--) | Returns true if there exists at least one slide that depends on this layout slide. |
| [getDependingSlides()](#getDependingSlides--) | Returns an array with all slides, which depend on this layout slide. |
| [remove()](#remove--) | Removes layout from presentation. |
| [getDrawingGuides()](#getDrawingGuides--) | Returns a collection of drawing guides for the layout slide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Zwraca menedżer HeaderFooter slajdu układu. Tylko do odczytu [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Zwraca:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

Zwraca menedżer placeholder slajdu układu. Tylko do odczytu [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

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

Zwraca layout type tego slajdu układu. Tylko do odczytu [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Zwraca:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Zwraca true, jeśli istnieje co najmniej jeden slide, który zależy od tego slajdu układu. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Zwraca tablicę ze wszystkimi slides, które zależą od tego slajdu układu.

**Zwraca:**
com.aspose.slides.ISlide[] - Array with all slides, which depend on this layout slide
### remove() {#remove--}
```
public abstract void remove()
```

Usuwa układ z prezentacji.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Zwraca kolekcję drawing guides dla slajdu układu. Tylko do odczytu [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Dodawanie nowego pionowego prowadnika rysunku po lewej stronie środka slajdu
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)