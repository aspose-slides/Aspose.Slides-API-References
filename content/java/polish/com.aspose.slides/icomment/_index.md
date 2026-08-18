---
title: IComment
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje komentarz na slajdzie.
type: docs
url: /pl/com.aspose.slides/icomment/
---```
public interface IComment
```

Reprezentuje komentarz na slajdzie.
## Metody

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Zwraca lub ustawia zwykły tekst komentarza slajdu. |
| [setText(String value)](#setText-java.lang.String-) | Zwraca lub ustawia zwykły tekst komentarza slajdu. |
| [getCreatedTime()](#getCreatedTime--) | Zwraca lub ustawia czas utworzenia komentarza. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Zwraca lub ustawia czas utworzenia komentarza. |
| [getSlide()](#getSlide--) | Zwraca lub ustawia slajd nadrzędny komentarza. |
| [getAuthor()](#getAuthor--) | Zwraca autora komentarza. |
| [getPosition()](#getPosition--) | Zwraca lub ustawia pozycję komentarza na slajdzie. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | Zwraca lub ustawia pozycję komentarza na slajdzie. |
| [remove()](#remove--) | Usuwa komentarz i wszystkie jego odpowiedzi z kolekcji nadrzędnej. |
| [getParentComment()](#getParentComment--) | Pobiera lub ustawia komentarz nadrzędny. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Pobiera lub ustawia komentarz nadrzędny. |
### getText() {#getText--}
```
public abstract String getText()
```


Zwraca lub ustawia zwykły tekst komentarza slajdu. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Zwraca lub ustawia zwykły tekst komentarza slajdu. Odczyt/zapis String.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```


Zwraca lub ustawia czas utworzenia komentarza. Ustawienie tej właściwości na java.util.Date(Long.MIN_VALUE) oznacza, że czas komentarza nie jest ustawiony. Odczyt/zapis java.util.Date.

--------------------

Czas komentarza jest opcjonalnym parametrem.

**Zwraca:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```


Zwraca lub ustawia czas utworzenia komentarza. Ustawienie tej właściwości na java.util.Date(Long.MIN_VALUE) oznacza, że czas komentarza nie jest ustawiony. Odczyt/zapis java.util.Date.

--------------------

Czas komentarza jest opcjonalnym parametrem.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```


Zwraca lub ustawia slajd nadrzędny komentarza. Tylko do odczytu [ISlide](../../com.aspose.slides/islide).

**Zwraca:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```


Zwraca autora komentarza. Tylko do odczytu [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Zwraca:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract Point2D.Float getPosition()
```


Zwraca lub ustawia pozycję komentarza na slajdzie. Odczyt/zapis java.awt.geom.Point2D.Float.

**Zwraca:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public abstract void setPosition(Point2D.Float value)
```


Zwraca lub ustawia pozycję komentarza na slajdzie. Odczyt/zapis java.awt.geom.Point2D.Float.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### remove() {#remove--}
```
public abstract void remove()
```


Usuwa komentarz i wszystkie jego odpowiedzi z kolekcji nadrzędnej.

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```


Pobiera lub ustawia komentarz nadrzędny. Odczyt/zapis [IComment](../../com.aspose.slides/icomment).

**Zwraca:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```


Pobiera lub ustawia komentarz nadrzędny. Odczyt/zapis [IComment](../../com.aspose.slides/icomment).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |