---
title: NotesSlide
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en notssida i en presentation.
type: docs
url: /sv/com.aspose.slides/notesslide/
---
**Arv:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Alla implementerade gränssnitt:**
[com.aspose.slides.INotesSlide](../../com.aspose.slides/inotesslide)
```
public class NotesSlide extends BaseSlide implements INotesSlide
```

Representerar en notssida i en presentation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returnerar HeaderFooter manager för notssidan. |
| [getNotesTextFrame()](#getNotesTextFrame--) | Returnerar en TextFrame med noternas text om det finns någon. |
| [getThemeManager()](#getThemeManager--) | Returnerar den överstyrande temahanteraren. |
| [getParentSlide()](#getParentSlide--) | Returnerar den överordnade bilden. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Anger om former på mastersidan ska visas på bilder eller inte. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Anger om former på mastersidan ska visas på bilder eller inte. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final INotesSlideHeaderFooterManager getHeaderFooterManager()
```

Returnerar HeaderFooter manager för notssidan. Endast läsning [INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager).

**Returnerar:**
[INotesSlideHeaderFooterManager](../../com.aspose.slides/inotesslideheaderfootermanager)
### getNotesTextFrame() {#getNotesTextFrame--}
```
public final ITextFrame getNotesTextFrame()
```

Returnerar en TextFrame med noternas text om det finns någon. Endast läsning [ITextFrame](../../com.aspose.slides/itextframe).

**Returnerar:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Returnerar den överstyrande temahanteraren. Endast läsning [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Returnerar:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getParentSlide() {#getParentSlide--}
```
public final ISlide getParentSlide()
```

Returnerar den överordnade bilden. Endast läsning [ISlide](../../com.aspose.slides/islide).

**Returnerar:**
[ISlide](../../com.aspose.slides/islide)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Anger om former på mastersidan ska visas på bilder eller inte. Läs/skriv boolean.

**Returnerar:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Anger om former på mastersidan ska visas på bilder eller inte. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |