---
title: IComment
second_title: Aspose.Slides for Android via Java API Reference
description: Egy megjegyzés a diára.
type: docs
url: /hu/com.aspose.slides/icomment/
---```
public interface IComment
```

Egy megjegyzés a diára.

## Metódusok

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Visszaadja vagy beállítja a dia megjegyzésének egyszerű szövegét. |
| [setText(String value)](#setText-java.lang.String-) | Visszaadja vagy beállítja a dia megjegyzésének egyszerű szövegét. |
| [getCreatedTime()](#getCreatedTime--) | Visszaadja vagy beállítja a megjegyzés létrehozásának időpontját. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Visszaadja vagy beállítja a megjegyzés létrehozásának időpontját. |
| [getSlide()](#getSlide--) | Visszaadja vagy beállítja a megjegyzés szülő diáját. |
| [getAuthor()](#getAuthor--) | Visszaadja a megjegyzés szerzőjét. |
| [getPosition()](#getPosition--) | Visszaadja vagy beállítja a megjegyzés pozícióját a dián. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Visszaadja vagy beállítja a megjegyzés pozícióját a dián. |
| [remove()](#remove--) | Eltávolítja a megjegyzést és minden válaszát a szülő gyűjteményből. |
| [getParentComment()](#getParentComment--) | Lekéri vagy beállítja a szülő megjegyzést. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Lekéri vagy beállítja a szülő megjegyzést. |

### getText() {#getText--}
```
public abstract String getText()
```

Visszaadja vagy beállítja a dia megjegyzésének egyszerű szövegét. Olvasás/írás String.

**Visszatér:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Visszaadja vagy beállítja a dia megjegyzésének egyszerű szövegét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Visszaadja vagy beállítja a megjegyzés létrehozásának időpontját. Ennek a tulajdonságnak a beállítása java.util.Date(Long.MIN_VALUE) értékre azt jelenti, hogy nincs megjegyzés időpont beállítva. Olvasás/írás java.util.Date.

**Visszatér:**
java.util.Date

--------------------

A megjegyzés időpontja opcionális paraméter.

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Visszaadja vagy beállítja a megjegyzés létrehozásának időpontját. Ennek a tulajdonságnak a beállítása java.util.Date(Long.MIN_VALUE) értékre azt jelenti, hogy nincs megjegyzés időpont beállítva. Olvasás/írás java.util.Date.

--------------------

A megjegyzés időpontja opcionális paraméter.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```

Visszaadja vagy beállítja a megjegyzés szülő diáját. Csak olvasható [ISlide](../../com.aspose.slides/islide).

**Visszatér:**
[ISlide](../../com.aspose.slides/islide)

### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

Visszaadja a megjegyzés szerzőjét. Csak olvasható [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Visszatér:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)

### getPosition() {#getPosition--}
```
public abstract PointF getPosition()
```

Visszaadja vagy beállítja a megjegyzés pozícióját a dián. Olvasás/írás android.graphics.PointF.

**Visszatér:**
android.graphics.PointF

### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public abstract void setPosition(PointF value)
```

Visszaadja vagy beállítja a megjegyzés pozícióját a dián. Olvasás/írás android.graphics.PointF.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public abstract void remove()
```

Eltávolítja a megjegyzést és annak minden válaszát a szülő gyűjteményből.

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

Lekéri vagy beállítja a szülő megjegyzést. Olvasás/írás [IComment](../../com.aspose.slides/icomment).

**Visszatér:**
[IComment](../../com.aspose.slides/icomment)

### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

Lekéri vagy beállítja a szülő megjegyzést. Olvasás/írás [IComment](../../com.aspose.slides/icomment).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |