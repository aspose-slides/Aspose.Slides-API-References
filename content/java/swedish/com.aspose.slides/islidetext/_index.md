---
title: ISlideText
second_title: Aspose.Slides för Java API-referens
description: Representerar den text som extraheras från bilden
type: docs
url: /sv/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

Representerar den text som extraheras från bilden
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getText()](#getText--) | Texten på bildens former |
| [getMasterText()](#getMasterText--) | Texten på mastersidans former för denna bild |
| [getLayoutText()](#getLayoutText--) | Texten på layoutsidans former för denna bild |
| [getNotesText()](#getNotesText--) | Texten på notssidans former för denna bild |
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


Texten på mastersidans former för denna bild

**Returnerar:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```


Texten på layoutsidans former för denna bild

**Returnerar:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```


Texten på notssidans former för denna bild

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