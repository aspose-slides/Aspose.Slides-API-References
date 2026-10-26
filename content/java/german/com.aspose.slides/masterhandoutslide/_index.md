---
title: MasterHandoutSlide
second_title: Aspose.Slides für Java API Reference
description: Stellt die Master-Folie für Handzettel dar.
type: docs
url: /de/com.aspose.slides/masterhandoutslide/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

Stellt die Master-Folien für Handzettel dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Gibt an, ob Formen auf der Master-Folien auf Folien angezeigt werden sollen oder nicht. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Gibt an, ob Formen auf der Master-Folien auf Folien angezeigt werden sollen oder nicht. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Gibt den HeaderFooter-Manager der Master-Handout-Folien zurück. |
| [getThemeManager()](#getThemeManager--) | Gibt den Theme-Manager zurück. |
| [getDrawingGuides()](#getDrawingGuides--) | Gibt eine Sammlung von Zeichenfuehrungen fuer die Master-Handout-Folien zurueck. |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Gibt an, ob Formen auf der Master-Folien auf Folien angezeigt werden sollen oder nicht. Fuer die Master-Folien selbst liefert diese Eigenschaft immer false zurueck. Lese/Schreib boolesch.

**Rueckgabe:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Gibt an, ob Formen auf der Master-Folien auf Folien angezeigt werden sollen oder nicht. Fuer die Master-Folien selbst liefert diese Eigenschaft immer false zurueck. Lese/Schreib boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

Gibt den HeaderFooter-Manager der Master-Handout-Folien zurueck. Nur lesbar [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Rueckgabe:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Gibt den Theme-Manager zurueck. Nur lesbar [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Rueckgabe:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Gibt eine Sammlung von Zeichenfuehrungen fuer die Master-Handout-Folien zurueck. Nur lesbar [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Hinzufügen der neuen horizontalen Zeichenführung über der Folienmitte
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rueckgabe:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)