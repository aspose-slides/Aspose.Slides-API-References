---
title: IComment
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a comment on a slide.
type: docs
url: /de/com.aspose.slides/icomment/
---```
public interface IComment
```

Stellt einen Kommentar zu einer Folie dar.
## Methoden

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Gibt den Nur-Text eines Folienkommentars zurück oder legt ihn fest. |
| [setText(String value)](#setText-java.lang.String-) | Gibt den Nur-Text eines Folienkommentars zurück oder legt ihn fest. |
| [getCreatedTime()](#getCreatedTime--) | Gibt die Erstellungszeit eines Kommentars zurück oder legt sie fest. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Gibt die Erstellungszeit eines Kommentars zurück oder legt sie fest. |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie eines Kommentars zurück oder legt sie fest. |
| [getAuthor()](#getAuthor--) | Gibt den Autor eines Kommentars zurück. |
| [getPosition()](#getPosition--) | Gibt die Position eines Kommentars auf einer Folie zurück oder legt sie fest. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Gibt die Position eines Kommentars auf einer Folie zurück oder legt sie fest. |
| [remove()](#remove--) | Entfernt den Kommentar und alle seine Antworten aus der übergeordneten Sammlung. |
| [getParentComment()](#getParentComment--) | Ruft den übergeordneten Kommentar ab oder legt ihn fest. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Ruft den übergeordneten Kommentar ab oder legt ihn fest. |
### getText() {#getText--}
```
public abstract String getText()
```

Gibt den Nur-Text eines Folienkommentars zurück oder legt ihn fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Gibt den Nur-Text eines Folienkommentars zurück oder legt ihn fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Gibt die Erstellungszeit eines Kommentars zurück oder legt sie fest. Das Setzen dieser Eigenschaft auf java.util.Date(Long.MIN_VALUE) bedeutet, dass keine Kommentarzeit festgelegt ist. Lesen/Schreiben java.util.Date.

--------------------

Die Kommentarzeit ist ein optionaler Parameter.

**Rückgabe:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Gibt die Erstellungszeit eines Kommentars zurück oder legt sie fest. Das Setzen dieser Eigenschaft auf java.util.Date(Long.MIN_VALUE) bedeutet, dass keine Kommentarzeit festgelegt ist. Lesen/Schreiben java.util.Date.

--------------------

Die Kommentarzeit ist ein optionaler Parameter.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.Date |  |
### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```

Gibt die übergeordnete Folie eines Kommentars zurück oder legt sie fest. Nur-Lesen [ISlide](../../com.aspose.slides/islide).

**Rückgabe:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

Gibt den Autor eines Kommentars zurück. Nur-Lesen [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Rückgabe:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract PointF getPosition()
```

Gibt die Position eines Kommentars auf einer Folie zurück oder legt sie fest. Lesen/Schreiben android.graphics.PointF.

**Rückgabe:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public abstract void setPosition(PointF value)
```

Gibt die Position eines Kommentars auf einer Folie zurück oder legt sie fest. Lesen/Schreiben android.graphics.PointF.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### remove() {#remove--}
```
public abstract void remove()
```

Entfernt den Kommentar und alle seine Antworten aus der übergeordneten Sammlung.
### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

Ruft den übergeordneten Kommentar ab oder legt ihn fest. Lesen/Schreiben [IComment](../../com.aspose.slides/icomment).

**Rückgabe:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

Ruft den übergeordneten Kommentar ab oder legt ihn fest. Lesen/Schreiben [IComment](../../com.aspose.slides/icomment).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |