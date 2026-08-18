---
title: LayoutSlide
second_title: Aspose.Slides für Java API Referenz
description: Stellt eine Layout-Folie dar.
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

Stellt eine Layout-Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Gibt den HeaderFooter-Manager der Layout-Folie zurück. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Gibt den Platzhalter-Manager der Layout-Folie zurück. |
| [getMasterSlide()](#getMasterSlide--) | Gibt oder setzt die Masterfolie für ein Layout. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Gibt oder setzt die Masterfolie für ein Layout. |
| [remove()](#remove--) | Entfernt das Layout aus der Präsentation. |
| [getThemeManager()](#getThemeManager--) | Gibt den überschreibenden Theme-Manager zurück. |
| [getLayoutType()](#getLayoutType--) | Gibt den Layouttyp dieser Layout-Folie zurück. |
| [getDependingSlides()](#getDependingSlides--) | Gibt ein Array mit allen Folien zurück, die von dieser Layout-Folie abhängen. |
| [hasDependingSlides()](#hasDependingSlides--) | Gibt wahr zurück, wenn mindestens eine Folie existiert, die von dieser Layout-Folie abhängt. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. |
| [getDrawingGuides()](#getDrawingGuides--) | Gibt eine Sammlung von Zeichenhilfen für die Layout-Folie zurück. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


Gibt den HeaderFooter-Manager der Layout-Folie zurück. Nur lesbar [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Rückgabe:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```


Gibt den Platzhalter-Manager der Layout-Folie zurück. Nur lesbar [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Rückgabe:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```


Gibt oder setzt die Masterfolie für ein Layout. Lesen/Schreiben [IMasterSlide](../../com.aspose.slides/imasterslide).

**Rückgabe:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```


Gibt oder setzt die Masterfolie für ein Layout. Lesen/Schreiben [IMasterSlide](../../com.aspose.slides/imasterslide).

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

**Rückgabe:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```


Gibt den Layouttyp dieser Layout-Folie zurück. Nur lesbar [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Rückgabe:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```


Gibt ein Array mit allen Folien zurück, die von dieser Layout-Folie abhängen.

**Rückgabe:**
com.aspose.slides.ISlide[] - Array von [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```


Gibt wahr zurück, wenn mindestens eine Folie existiert, die von dieser Layout-Folie abhängt. Nur lesbar  boolean .

**Rückgabe:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. Lesen/Schreiben  boolean .

**Rückgabe:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. Lesen/Schreiben  boolean .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Gibt eine Sammlung von Zeichenhilfen für die Layout-Folie zurück. Nur lesbar [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
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