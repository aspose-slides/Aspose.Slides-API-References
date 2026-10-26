---
title: ISlideText
second_title: Aspose.Slides for Java API Reference
description: A diáról kinyert szöveget képviseli
type: docs
url: /hu/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

A diáról kinyert szöveget képviseli
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getText()](#getText--) | The text on the slide's shapes |
| [getMasterText()](#getMasterText--) | The text on the master page's shapes for this slide |
| [getLayoutText()](#getLayoutText--) | The text on the layout page's shapes for this slide |
| [getNotesText()](#getNotesText--) | The text on the notes page's shapes for this slide |
| [getCommentsText()](#getCommentsText--) | The text of the slide comments |
### getText() {#getText--}
```
public abstract String getText()
```


A dián lévő alakzatok szövege

**Returns:**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```


A diához tartozó mesteroldal alakzatainak szövege

**Returns:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```


A diához tartozó elrendezésoldal alakzatainak szövege

**Returns:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```


A diához tartozó jegyzetoldal alakzatainak szövege

**Returns:**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```


A dia megjegyzéseinek szövege

--------------------

Ez a mező üres, ha a szöveget az Arranged módon vonják ki.

**Returns:**
java.lang.String