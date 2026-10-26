---
title: ILayoutSlide
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt eine Layout-Folie dar.
type: docs
url: /de/com.aspose.slides/ilayoutslide/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Stellt eine Layout-Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Gibt den HeaderFooter-Manager der Layout-Folie zurück. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Gibt den Platzhalter-Manager der Layout-Folie zurück. |
| [getMasterSlide()](#getMasterSlide--) | Gibt die Master-Folie für ein Layout zurück oder setzt sie. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Gibt die Master-Folie für ein Layout zurück oder setzt sie. |
| [getLayoutType()](#getLayoutType--) | Gibt den Layouttyp dieser Layout-Folie zurück. |
| [hasDependingSlides()](#hasDependingSlides--) | Gibt true zurück, wenn mindestens eine Folie von dieser Layout-Folie abhängt. |
| [getDependingSlides()](#getDependingSlides--) | Gibt ein Array mit allen Folien zurück, die von dieser Layout-Folie abhängen. |
| [remove()](#remove--) | Entfernt das Layout aus der Präsentation. |
| [getDrawingGuides()](#getDrawingGuides--) | Gibt eine Sammlung von Zeichenhilfen für die Layout-Folie zurück. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Gibt den HeaderFooter-Manager der Layout-Folie zurück. Nur-Lesen [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Rückgabe:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

Gibt den Platzhalter-Manager der Layout-Folie zurück. Nur-Lesen [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Rückgabe:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```

Gibt die Master-Folie für ein Layout zurück oder setzt sie. Lesen/Schreiben [IMasterSlide](../../com.aspose.slides/imasterslide).

**Rückgabe:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```

Gibt die Master-Folie für ein Layout zurück oder setzt sie. Lesen/Schreiben [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```

Gibt den Layouttyp dieser Layout-Folie zurück. Nur-Lesen [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Rückgabe:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Gibt true zurück, wenn mindestens eine Folie von dieser Layout-Folie abhängt. Nur-Lesen boolean.

**Rückgabe:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Gibt ein Array mit allen Folien zurück, die von dieser Layout-Folie abhängen.

**Rückgabe:**
com.aspose.slides.ISlide[] - Array mit allen Folien, die von dieser Layout-Folie abhängen
### remove() {#remove--}
```
public abstract void remove()
```

Entfernt das Layout aus der Präsentation.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Gibt eine Sammlung von Zeichenhilfen für die Layout-Folie zurück. Nur-Lesen [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Hinzufügen des neuen vertikalen Zeichenleitfadens links von der Folienmitte
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)