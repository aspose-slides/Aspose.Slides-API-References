---
title: NotesSlide
second_title: Aspose.Slides für Android über die Java API Referenz
description: Stellt eine Notizfolie in einer Präsentation dar.
type: docs
url: /de/com.aspose.slides/notesslide/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**All Implemented Interfaces:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

Stellt eine Notizfolie in einer Präsentation dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Gibt den HeaderFooter Manager der Notizfolie zurück. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Gibt ein TextFrame mit dem Notiztext zurück, falls vorhanden. |
| [getThemeManager()](#getThemeManager--) | Gibt den überschreibenden Theme-Manager zurück. |
| [getParentSlide()](#getParentSlide--) | Gibt die übergeordnete Folie zurück. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Legt fest, ob Formen auf der Masterfolie in den Folien angezeigt werden sollen oder nicht. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Legt fest, ob Formen auf der Masterfolie in den Folien angezeigt werden sollen oder nicht. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```


Gibt den HeaderFooter Manager der Notizfolie zurück. Nur lesbar [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

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


Gibt den überschreibenden Theme-Manager zurück. Nur lesbar [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

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


Legt fest, ob Formen auf der Masterfolie in den Folien angezeigt werden sollen oder nicht. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Legt fest, ob Formen auf der Masterfolie in den Folien angezeigt werden sollen oder nicht. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |