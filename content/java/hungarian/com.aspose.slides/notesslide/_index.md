---
title: NotesSlide
second_title: Aspose.Slides Java API referencia
description: Egy jegyzet diát képvisel egy prezentációban.
type: docs
url: /hu/com.aspose.slides/notesslide/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**All Implemented Interfaces:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

Egy jegyzet dia képviseli egy prezentációban.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a jegyzetdia HeaderFooter kezelőjét. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Visszaad egy TextFrame-et a jegyzet szöveggel, ha létezik. |
| [getThemeManager()](#getThemeManager--) | Visszaadja a felülbíráló téma kezelőt. |
| [getParentSlide()](#getParentSlide--) | Visszaadja a szülő diát. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Megadja, hogy a mester dián lévő alakzatok megjelenjenek-e a diákon vagy sem. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Megadja, hogy a mester dián lévő alakzatok megjelenjenek-e a diákon vagy sem. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```


Visszaadja a jegyzetdia HeaderFooter kezelőjét. Csak olvasható [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Visszatér:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```


Visszaad egy TextFrame-et a jegyzet szöveggel, ha létezik. Csak olvasható [ITextFrame](../../com.aspose.slides/itextframe).

**Visszatér:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


Visszaadja a felülbíráló téma kezelőt. Csak olvasható [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Visszatér:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```


Visszaadja a szülő diát. Csak olvasható [ISlide](../../com.aspose.slides/islide).

**Visszatér:**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Megadja, hogy a mester dián lévő alakzatok megjelenjenek-e a diákon vagy sem. Olvasás/írás boolean.

**Visszatér:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Megadja, hogy a mester dián lévő alakzatok megjelenjenek-e a diákon vagy sem. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |