---
title: IComment
second_title: Aspose.Slides for Java API Reference
description: Representerar en kommentar på en bild.
type: docs
url: /sv/com.aspose.slides/icomment/
---```
public interface IComment
```

Representerar en kommentar på en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getText()](#getText--) | Returnerar eller anger den enkla texten för en bildkommentar. |
| [setText(String value)](#setText-java.lang.String-) | Returnerar eller anger den enkla texten för en bildkommentar. |
| [getCreatedTime()](#getCreatedTime--) | Returnerar eller anger tiden för en kommentarsskapning. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Returnerar eller anger tiden för en kommentarsskapning. |
| [getSlide()](#getSlide--) | Returnerar eller anger föräldrabilden för en kommentar. |
| [getAuthor()](#getAuthor--) | Returnerar författaren till en kommentar. |
| [getPosition()](#getPosition--) | Returnerar eller anger positionen för en kommentar på en bild. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | Returnerar eller anger positionen för en kommentar på en bild. |
| [remove()](#remove--) | Tar bort kommentaren och alla dess svar från föräldrasamlingen. |
| [getParentComment()](#getParentComment--) | Hämtar eller anger föräldrakommentar. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Hämtar eller anger föräldrakommentar. |
### getText() {#getText--}
```
public abstract String getText()
```

Returnerar eller anger den enkla texten för en bildkommentar. Läs/skriv String.

**Returnerar:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Returnerar eller anger den enkla texten för en bildkommentar. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Returnerar eller anger tiden för en kommentarsskapning. Att sätta denna egenskap till java.util.Date(Long.MIN\_VALUE) betyder att ingen kommentarstid är angiven. Läs/skriv java.util.Date.

--------------------

Kommentartiden är en valfri parameter.

**Returnerar:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Returnerar eller anger tiden för en kommentarsskapning. Att sätta denna egenskap till java.util.Date(Long.MIN\_VALUE) betyder att ingen kommentarstid är angiven. Läs/skriv java.util.Date.

--------------------

Kommentartiden är en valfri parameter.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.Date |  |
### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```

Returnerar eller anger föräldrabilden för en kommentar. Endast läsning [ISlide](../../com.aspose.slides/islide).

**Returnerar:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

Returnerar författaren till en kommentar. Endast läsning [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Returnerar:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract Point2D.Float getPosition()
```

Returnerar eller anger positionen för en kommentar på en bild. Läs/skriv java.awt.geom.Point2D.Float.

**Returnerar:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public abstract void setPosition(Point2D.Float value)
```

Returnerar eller anger positionen för en kommentar på en bild. Läs/skriv java.awt.geom.Point2D.Float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### remove() {#remove--}
```
public abstract void remove()
```

Tar bort kommentaren och alla dess svar från föräldrasamlingen.

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

Hämtar eller anger föräldrakommentar. Läs/skriv [IComment](../../com.aspose.slides/icomment).

**Returnerar:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

Hämtar eller anger föräldrakommentar. Läs/skriv [IComment](../../com.aspose.slides/icomment).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |