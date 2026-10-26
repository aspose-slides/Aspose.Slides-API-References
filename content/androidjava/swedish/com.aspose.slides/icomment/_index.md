---
title: IComment
second_title: Aspose.Slides för Android via Java API-referens
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
| [getText()](#getText--) | Returnerar eller anger vanlig text för en bildkommentar. |
| [setText(String value)](#setText-java.lang.String-) | Returnerar eller anger vanlig text för en bildkommentar. |
| [getCreatedTime()](#getCreatedTime--) | Returnerar eller anger tiden för när kommentaren skapades. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Returnerar eller anger tiden för när kommentaren skapades. |
| [getSlide()](#getSlide--) | Returnerar eller anger den överordnade bilden för en kommentar. |
| [getAuthor()](#getAuthor--) | Returnerar författaren till en kommentar. |
| [getPosition()](#getPosition--) | Returnerar eller anger positionen för en kommentar på en bild. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Returnerar eller anger positionen för en kommentar på en bild. |
| [remove()](#remove--) | Tar bort kommentaren och alla dess svar från den överordnade samlingen. |
| [getParentComment()](#getParentComment--) | Hämtar eller anger föräldrakommentar. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Hämtar eller anger föräldrakommentar. |
### getText() {#getText--}
```
public abstract String getText()
```


Returnerar eller anger vanlig text för en bildkommentar. Läs/skriv String.

**Returnerar:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Returnerar eller anger vanlig text för en bildkommentar. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```


Returnerar eller anger tiden för när kommentaren skapades. Att sätta denna egenskap till java.util.Date(Long.MIN\_VALUE) betyder att ingen kommentarstid är angiven. Läs/skriv java.util.Date.

--------------------

Kommentarstiden är en valfri parameter.

**Returnerar:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```


Returnerar eller anger tiden för när kommentaren skapades. Att sätta denna egenskap till java.util.Date(Long.MIN\_VALUE) betyder att ingen kommentarstid är angiven. Läs/skriv java.util.Date.

--------------------

Kommentarstiden är en valfri parameter.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.Date |  |
### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```


Returnerar eller anger den överordnade bilden för en kommentar. Skrivskyddad [ISlide](../../com.aspose.slides/islide).

**Returnerar:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```


Returnerar författaren till en kommentar. Skrivskyddad [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Returnerar:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract PointF getPosition()
```


Returnerar eller anger positionen för en kommentar på en bild. Läs/skriv android.graphics.PointF.

**Returnerar:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public abstract void setPosition(PointF value)
```


Returnerar eller anger positionen för en kommentar på en bild. Läs/skriv android.graphics.PointF.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### remove() {#remove--}
```
public abstract void remove()
```


Tar bort kommentaren och alla dess svar från den överordnade samlingen.

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