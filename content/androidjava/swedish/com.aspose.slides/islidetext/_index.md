---
title: ISlideText
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the text extracted from the slide
type: docs
url: /sv/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

Representerar texten som extraheras från bilden
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getText()](#getText--) | Texten på bildens former |
| [getMasterText()](#getMasterText--) | Texten på master-sidans former för den här bilden |
| [getLayoutText()](#getLayoutText--) | Texten på layoutsidans former för den här bilden |
| [getNotesText()](#getNotesText--) | Texten på notes-sidans former för den här bilden |
| [getCommentsText()](#getCommentsText--) | Texten i bildens kommentarer |
### getText() {#getText--}
```
public abstract String getText()
```


Texten på bildens former

**Returnerar:**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```


Texten på master-sidans former för den här bilden

**Returnerar:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```


Texten på layoutsidans former för den här bilden

**Returnerar:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```


Texten på notes-sidans former för den här bilden

**Returnerar:**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```


Texten i bildens kommentarer

--------------------

Detta fält är tomt när texten extraheras med Arranged-läget.

**Returnerar:**
java.lang.String