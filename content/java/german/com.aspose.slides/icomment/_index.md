---
title: IComment
second_title: Aspose.Slides for Java API Reference
description: Stellt einen Kommentar auf einer Folie dar.
type: docs
url: /de/com.aspose.slides/icomment/
---```
public interface IComment
```

Stellt einen Kommentar auf einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getText()](#getText--) | Gibt den Klartext eines Folienkommentars zurück oder legt ihn fest. |
| [setText(String value)](#setText-java.lang.String-) | Gibt den Klartext eines Folienkommentars zurück oder legt ihn fest. |
| [getCreatedTime()](#getCreatedTime--) | Gibt die Erstellungszeit eines Kommentars zurück oder legt sie fest. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Gibt die Erstellungszeit eines Kommentars zurück oder legt sie fest. |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie eines Kommentars zurück oder legt sie fest. |
| [getAuthor()](#getAuthor--) | Gibt den Autor eines Kommentars zurück. |
| [getPosition()](#getPosition--) | Gibt die Position eines Kommentars auf einer Folie zurück oder legt sie fest. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | Gibt die Position eines Kommentars auf einer Folie zurück oder legt sie fest. |
| [remove()](#remove--) | Entfernt den Kommentar und alle seine Antworten aus der übergeordneten Sammlung. |
| [getParentComment()](#getParentComment--) | Liest oder legt den übergeordneten Kommentar fest. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Liest oder legt den übergeordneten Kommentar fest. |
### getText() {#getText--}
```
public abstract String getText()
```

Gibt den Klartext eines Folienkommentars zurück oder legt ihn fest. Lesen/Schreiben String.

**Rückgabewert:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Gibt den Klartext eines Folienkommentars zurück oder legt ihn fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Gibt die Erstellungszeit eines Kommentars zurück oder legt sie fest. Das Setzen dieser Eigenschaft auf java.util.Date(Long.MIN\_VALUE) bedeutet, dass keine Kommentarzeit festgelegt ist. Lesen/Schreiben java.util.Date.

--------------------

Die Kommentarzeit ist ein optionaler Parameter.

**Rückgabewert:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Gibt die Erstellungszeit eines Kommentars zurück oder legt sie fest. Das Setzen dieser Eigenschaft auf java.util.Date(Long.MIN\_VALUE) bedeutet, dass keine Kommentarzeit festgelegt ist. Lesen/Schreiben java.util.Date.

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

**Rückgabewert:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

Gibt den Autor eines Kommentars zurück. Nur-Lesen [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Rückgabewert:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract Point2D.Float getPosition()
```

Gibt die Position eines Kommentars auf einer Folie zurück oder legt sie fest. Lesen/Schreiben java.awt.geom.Point2D.Float.

**Rückgabewert:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public abstract void setPosition(Point2D.Float value)
```

Gibt die Position eines Kommentars auf einer Folie zurück oder legt sie fest. Lesen/Schreiben java.awt.geom.Point2D.Float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### remove() {#remove--}
```
public abstract void remove()
```

Entfernt den Kommentar und alle seine Antworten aus der übergeordneten Sammlung.
### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

Liest oder legt den übergeordneten Kommentar fest. Lesen/Schreiben [IComment](../../com.aspose.slides/icomment).

**Rückgabewert:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

Liest oder legt den übergeordneten Kommentar fest. Lesen/Schreiben [IComment](../../com.aspose.slides/icomment).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |