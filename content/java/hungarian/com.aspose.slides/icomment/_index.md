---
title: IComment
second_title: Aspose.Slides for Java API Reference
description: Represents a comment on a slide.
type: docs
url: /hu/com.aspose.slides/icomment/
---```
public interface IComment
```

A dián egy megjegyzést ábrázol.
## Módszerek

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Visszaadja vagy beállítja egy diamegjegyzés egyszerű szövegét. |
| [setText(String value)](#setText-java.lang.String-) | Visszaadja vagy beállítja egy diamegjegyzés egyszerű szövegét. |
| [getCreatedTime()](#getCreatedTime--) | Visszaadja vagy beállítja egy megjegyzés létrehozásának időpontját. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Visszaadja vagy beállítja egy megjegyzés létrehozásának időpontját. |
| [getSlide()](#getSlide--) | Visszaadja vagy beállítja egy megjegyzés szülődiáját. |
| [getAuthor()](#getAuthor--) | Visszaadja egy megjegyzés szerzőjét. |
| [getPosition()](#getPosition--) | Visszaadja vagy beállítja egy megjegyzés helyzetét a dián. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | Visszaadja vagy beállítja egy megjegyzés helyzetét a dián. |
| [remove()](#remove--) | Eltávolítja a megjegyzést és annak összes válaszát a szülőgyűjteményből. |
| [getParentComment()](#getParentComment--) | Visszaadja vagy beállítja a szülő megjegyzést. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Visszaadja vagy beállítja a szülő megjegyzést. |
### getText() {#getText--}
```
public abstract String getText()
```


Visszaadja vagy beállítja egy diamegjegyzés egyszerű szövegét. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Visszaadja vagy beállítja egy diamegjegyzés egyszerű szövegét. Olvasás/írás String.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```


Visszaadja vagy beállítja egy megjegyzés létrehozásának időpontját. Ha ezt a tulajdonságot java.util.Date(Long.MIN_VALUE)-re állítja, azt jelenti, hogy nincs beállítva megjegyzésidő. Olvasás/írás java.util.Date.

--------------------

A megjegyzés időpontja opcionális paraméter.

**Visszatér:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```


Visszaadja vagy beállítja egy megjegyzés létrehozásának időpontját. Ha ezt a tulajdonságot java.util.Date(Long.MIN_VALUE)-re állítja, azt jelenti, hogy nincs beállítva megjegyzésidő. Olvasás/írás java.util.Date.

--------------------

A megjegyzés időpontja opcionális paraméter.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```


Visszaadja vagy beállítja egy megjegyzés szülődiáját. Csak olvasható [ISlide](../../com.aspose.slides/islide).

**Visszatér:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```


Visszaadja egy megjegyzés szerzőjét. Csak olvasható [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Visszatér:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract Point2D.Float getPosition()
```


Visszaadja vagy beállítja egy megjegyzés helyzetét a dián. Olvasás/írás java.awt.geom.Point2D.Float.

**Visszatér:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public abstract void setPosition(Point2D.Float value)
```


Visszaadja vagy beállítja egy megjegyzés helyzetét a dián. Olvasás/írás java.awt.geom.Point2D.Float.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### remove() {#remove--}
```
public abstract void remove()
```


Eltávolítja a megjegyzést és annak összes válaszát a szülőgyűjteményből.

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```


Visszaadja vagy beállítja a szülő megjegyzést. Olvasás/írás [IComment](../../com.aspose.slides/icomment).

**Visszatér:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```


Visszaadja vagy beállítja a szülő megjegyzést. Olvasás/írás [IComment](../../com.aspose.slides/icomment).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |