---
title: NotesSlide
second_title: Aspose.Slides for Android Java API referencia
description: Egy jegyzetdiát ábrázol egy bemutatóban.
type: docs
url: /hu/com.aspose.slides/notesslide/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Minden megvalósított interfész:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

Egy jegyzetdia reprezentálás egy bemutatóban.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a jegyzetdia HeaderFooter kezelőjét. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Visszaad egy TextFrame-et a jegyzet szövegével, ha van. |
| [getThemeManager()](#getThemeManager--) | Visszaadja a felülíró téma kezelőt. |
| [getParentSlide()](#getParentSlide--) | Visszaadja a szülődiát. |
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


Visszaad egy TextFrame-et a jegyzet szövegével, ha van. Csak olvasható [ITextFrame](../../com.aspose.slides/itextframe).

**Visszatér:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


Visszaadja a felülíró téma kezelőt. Csak olvasható [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Visszatér:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```


Visszaadja a szülődiát. Csak olvasható [ISlide](../../com.aspose.slides/islide).

**Visszatér:**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Megadja, hogy a mester dián lévő alakzatok megjelenjenek-e a diákon vagy sem. Olvasási/írási boolean.

**Visszatér:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Megadja, hogy a mester dián lévő alakzatok megjelenjenek-e a diákon vagy sem. Olvasási/írási boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |