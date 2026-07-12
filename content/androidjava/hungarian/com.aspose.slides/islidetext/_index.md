---
title: ISlideText
second_title: Aspose.Slides for Android via Java API hivatkozás
description: A diáról kinyert szöveget képviseli
type: docs
url: /hu/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

A diáról kinyert szöveget képviseli
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getText()](#getText--) | A dia alakzatainak szövege |
| [getMasterText()](#getMasterText--) | A diához tartozó mesteroldal alakzatainak szövege |
| [getLayoutText()](#getLayoutText--) | A diához tartozó elrendezésoldal alakzatainak szövege |
| [getNotesText()](#getNotesText--) | A diához tartozó jegyzetoldal alakzatainak szövege |
| [getCommentsText()](#getCommentsText--) | A dia megjegyzéseinek szövege |
### getText() {#getText--}
```
public abstract String getText()
```

A dia alakzatainak szövege

**Visszatér:**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```

A diához tartozó mesteroldal alakzatainak szövege

**Visszatér:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```

A diához tartozó elrendezésoldal alakzatainak szövege

**Visszatér:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```

A diához tartozó jegyzetoldal alakzatainak szövege

**Visszatér:**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```

A dia megjegyzéseinek szövege

--------------------

Ez a mező üres, ha a szöveget az Arranged móddal vonják ki.

**Visszatér:**
java.lang.String