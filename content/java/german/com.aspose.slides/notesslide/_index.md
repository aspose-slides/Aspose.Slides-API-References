---
title: NotesSlide
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Notizfolie in einer Präsentation dar.
type: docs
url: /de/com.aspose.slides/notesslide/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

Stellt eine Notizfolie in einer Präsentation dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Gibt den HeaderFooter-Manager der Notizfolie zurück. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Gibt ein TextFrame mit dem Notiztext zurück, falls vorhanden. |
| [getThemeManager()](#getThemeManager--) | Gibt den übergeordneten Theme-Manager zurück. |
| [getParentSlide()](#getParentSlide--) | Gibt die übergeordnete Folie zurück. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Gibt an, ob Formen auf der Masterfolie auf den Folien angezeigt werden sollen oder nicht. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Gibt an, ob Formen auf der Masterfolie auf den Folien angezeigt werden sollen oder nicht. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Gibt den HeaderFooter-Manager der Notizfolie zurück. Nur lesbar [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Rückgabe:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```

Gibt ein TextFrame mit dem Notiztext zurück, falls vorhanden. Nur lesbar [ITextFrame](../../com.aspose.slides/itextframe).

**Rückgabe:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Gibt den übergeordneten Theme-Manager zurück. Nur lesbar [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Rückgabe:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```

Gibt die übergeordnete Folie zurück. Nur lesbar [ISlide](../../com.aspose.slides/islide).

**Rückgabe:**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Gibt an, ob Formen auf der Masterfolie auf den Folien angezeigt werden sollen oder nicht. Lese-/Schreib-Boolean.

**Rückgabe:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Gibt an, ob Formen auf der Masterfolie auf den Folien angezeigt werden sollen oder nicht. Lese-/Schreib-Boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |