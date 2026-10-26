---
title: MasterNotesSlide
second_title: Aspose.Slides für Android über die Java API Referenz
description: Repräsentiert die Master-Folie für Notizen.
type: docs
url: /de/com.aspose.slides/masternotesslide/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

Repräsentiert die Master-Folien für Notizen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Gibt an, ob Formen auf der Master-Folien angezeigt werden sollen oder nicht. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Gibt an, ob Formen auf der Master-Folien angezeigt werden sollen oder nicht. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Gibt den HeaderFooter-Manager der Master-Notizfolie zurück. |
| [getThemeManager()](#getThemeManager--) | Gibt den Theme-Manager zurück. |
| [getNotesStyle()](#getNotesStyle--) | Gibt den Stil eines Notiztextes zurück. |
| [getDrawingGuides()](#getDrawingGuides--) | Gibt eine Sammlung von Zeichenhilfen für die Master-Notizfolie zurück. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Gibt an, ob Formen auf der Master-Folien angezeigt werden sollen oder nicht. Für die Master-Folie selbst gibt diese Eigenschaft immer false zurück. Lese/Schreib-Boolean.

**Rückgabewert:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Gibt an, ob Formen auf der Master-Folien angezeigt werden sollen oder nicht. Für die Master-Folie selbst gibt diese Eigenschaft immer false zurück. Lese/Schreib-Boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

Gibt den HeaderFooter-Manager der Master-Notizfolie zurück. Nur-Lese [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Rückgabewert:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Gibt den Theme-Manager zurück. Nur-Lese [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Rückgabewert:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```

Gibt den Stil eines Notiztextes zurück. Nur-Lese [ITextStyle](../../com.aspose.slides/itextstyle).

**Rückgabewert:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Gibt eine Sammlung von Zeichenhilfen für die Master-Notizfolie zurück. Nur-Lese [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Hinzufügen der neuen horizontalen Zeichenhilfe unterhalb der Folienmitte
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabewert:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)