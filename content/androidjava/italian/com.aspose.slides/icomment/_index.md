---
title: IComment
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta un commento su una diapositiva.
type: docs
url: /it/com.aspose.slides/icomment/
---```
public interface IComment
```

Rappresenta un commento su una diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getText()](#getText--) | Returns or sets the plain text of a slide comment. |
| [setText(String value)](#setText-java.lang.String-) | Returns or sets the plain text of a slide comment. |
| [getCreatedTime()](#getCreatedTime--) | Returns or sets the time of a comment creation. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Returns or sets the time of a comment creation. |
| [getSlide()](#getSlide--) | Returns or sets the parent slide of a comment. |
| [getAuthor()](#getAuthor--) | Returns the author of a comment. |
| [getPosition()](#getPosition--) | Returns or sets the position of a comment on a slide. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Returns or sets the position of a comment on a slide. |
| [remove()](#remove--) | Removes comment and all its replies from the parent collection. |
| [getParentComment()](#getParentComment--) | Gets or sets parent comment. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Gets or sets parent comment. |
### getText() {#getText--}
```
public abstract String getText()
```

Restituisce o imposta il testo semplice di un commento su una diapositiva. Lettura/scrittura String.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Restituisce o imposta il testo semplice di un commento su una diapositiva. Lettura/scrittura String.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Restituisce o imposta l'ora di creazione di un commento. Impostare questa proprietà su java.util.Date(Long.MIN_VALUE) indica che non è impostata alcuna ora del commento. Lettura/scrittura java.util.Date.

--------------------

Il tempo del commento è un parametro opzionale.

**Returns:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Restituisce o imposta l'ora di creazione di un commento. Impostare questa proprietà su java.util.Date(Long.MIN_VALUE) indica che non è impostata alcuna ora del commento. Lettura/scrittura java.util.Date.

--------------------

Il tempo del commento è un parametro opzionale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.Date |  |
### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```

Restituisce o imposta la diapositiva genitore di un commento. Solo lettura [ISlide](../../com.aspose.slides/islide).

**Returns:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

Restituisce l'autore di un commento. Solo lettura [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Returns:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract PointF getPosition()
```

Restituisce o imposta la posizione di un commento su una diapositiva. Lettura/scrittura android.graphics.PointF.

**Returns:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public abstract void setPosition(PointF value)
```

Restituisce o imposta la posizione di un commento su una diapositiva. Lettura/scrittura android.graphics.PointF.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### remove() {#remove--}
```
public abstract void remove()
```

Rimuove il commento e tutte le sue risposte dalla collezione genitore.
### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

Ottiene o imposta il commento genitore. Lettura/scrittura [IComment](../../com.aspose.slides/icomment).

**Returns:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

Ottiene o imposta il commento genitore. Lettura/scrittura [IComment](../../com.aspose.slides/icomment).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |