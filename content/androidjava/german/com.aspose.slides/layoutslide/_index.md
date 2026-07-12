---
title: LayoutSlide
second_title: Aspose.Slides für Android über die Java API Referenz
description: Stellt eine Layoutfolie dar.
type: docs
url: /de/com.aspose.slides/layoutslide/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

Stellt eine Layoutfolie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Gibt den HeaderFooter-Manager der Layoutfolie zurück. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Gibt den Platzhalter-Manager der Layoutfolie zurück. |
| [getMasterSlide()](#getMasterSlide--) | Gibt die Master-Folie zurück oder setzt sie für ein Layout. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Gibt die Master-Folie zurück oder setzt sie für ein Layout. |
| [remove()](#remove--) | Entfernt das Layout aus der Präsentation. |
| [getThemeManager()](#getThemeManager--) | Gibt den überschreibenden Theme-Manager zurück. |
| [getLayoutType()](#getLayoutType--) | Gibt den Layouttyp dieser Layoutfolie zurück. |
| [getDependingSlides()](#getDependingSlides--) | Gibt ein Array mit allen Folien zurück, die von dieser Layoutfolie abhängen. |
| [hasDependingSlides()](#hasDependingSlides--) | Gibt true zurück, wenn mindestens eine Folie von dieser Layoutfolie abhängt. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Gibt an, ob Formen auf der Master-Folie auf Folien angezeigt werden sollen oder nicht. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Gibt an, ob Formen auf der Master-Folie auf Folien angezeigt werden sollen oder nicht. |
| [getDrawingGuides()](#getDrawingGuides--) | Gibt eine Sammlung von Zeichen-Hilfslinien für die Layoutfolie zurück. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Gibt den HeaderFooter-Manager der Layoutfolie zurück. Nur lesbar [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Rückgabewert:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```

Gibt den Platzhalter-Manager der Layoutfolie zurück. Nur lesbar [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Rückgabewert:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```

Gibt die Master-Folie zurück oder setzt sie für ein Layout. Lesen/Schreiben [IMasterSlide](../../com.aspose.slides/imasterslide).

**Rückgabewert:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```

Gibt die Master-Folie zurück oder setzt sie für ein Layout. Lesen/Schreiben [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### remove() {#remove--}
```
public final void remove()
```

Entfernt das Layout aus der Präsentation.
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Gibt den überschreibenden Theme-Manager zurück. Nur lesbar [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Rückgabewert:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```

Gibt den Layouttyp dieser Layoutfolie zurück. Nur lesbar [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Rückgabewert:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Gibt ein Array mit allen Folien zurück, die von dieser Layoutfolie abhängen.

**Rückgabewert:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Gibt true zurück, wenn mindestens eine Folie von dieser Layoutfolie abhängt. Nur lesbar  boolean .

**Rückgabewert:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Gibt an, ob Formen auf der Master-Folie auf Folien angezeigt werden sollen oder nicht. Lesen/Schreiben  boolean .

**Rückgabewert:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Gibt an, ob Formen auf der Master-Folie auf Folien angezeigt werden sollen oder nicht. Lesen/Schreiben  boolean .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Gibt eine Sammlung von Zeichen-Hilfslinien für die Layoutfolie zurück. Nur lesbar [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Hinzufügen der neuen vertikalen Zeichenhilfslinie links vom Folienmittelpunkt
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabewert:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)