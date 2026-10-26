---
title: ISlideText
second_title: Aspose.Slides für Android über Java-API-Referenz
description: Stellt den aus der Folie extrahierten Text dar
type: docs
url: /de/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

Stellt den aus der Folie extrahierten Text dar
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getText()](#getText--) | Der Text in den Formen der Folie |
| [getMasterText()](#getMasterText--) | Der Text in den Formen der Masterseite für diese Folie |
| [getLayoutText()](#getLayoutText--) | Der Text in den Formen der Layoutseite für diese Folie |
| [getNotesText()](#getNotesText--) | Der Text in den Formen der Notizenseite für diese Folie |
| [getCommentsText()](#getCommentsText--) | Der Text der Folienkommentare |
### getText() {#getText--}
```
public abstract String getText()
```


Der Text in den Formen der Folie

**Rückgabewert:**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```


Der Text in den Formen der Masterseite für diese Folie

**Rückgabewert:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```


Der Text in den Formen der Layoutseite für diese Folie

**Rückgabewert:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```


Der Text in den Formen der Notizenseite für diese Folie

**Rückgabewert:**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```


Der Text der Folienkommentare

--------------------

Dieses Feld ist leer, wenn der Text im Arranged-Modus extrahiert wird.

**Rückgabewert:**
java.lang.String