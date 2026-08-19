---
title: IComment
second_title: Aspose.Slides for Java API Reference
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
| [getText()](#getText--) | Restituisce o imposta il testo semplice di un commento su una diapositiva. |
| [setText(String value)](#setText-java.lang.String-) | Restituisce o imposta il testo semplice di un commento su una diapositiva. |
| [getCreatedTime()](#getCreatedTime--) | Restituisce o imposta il tempo di creazione di un commento. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Restituisce o imposta il tempo di creazione di un commento. |
| [getSlide()](#getSlide--) | Restituisce o imposta la diapositiva padre di un commento. |
| [getAuthor()](#getAuthor--) | Restituisce l'autore di un commento. |
| [getPosition()](#getPosition--) | Restituisce o imposta la posizione di un commento su una diapositiva. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | Restituisce o imposta la posizione di un commento su una diapositiva. |
| [remove()](#remove--) | Rimuove il commento e tutte le sue risposte dalla raccolta padre. |
| [getParentComment()](#getParentComment--) | Ottiene o imposta il commento padre. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Ottiene o imposta il commento padre. |
### getText() {#getText--}
```
public abstract String getText()
```


Restituisce o imposta il testo semplice di un commento su una diapositiva. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Restituisce o imposta il testo semplice di un commento su una diapositiva. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```


Restituisce o imposta il tempo di creazione di un commento. Impostare questa proprietà su java.util.Date(Long.MIN_VALUE) significa che non è impostato alcun tempo per il commento. Lettura/Scrittura java.util.Date.

--------------------

Il tempo del commento è un parametro opzionale.

**Restituisce:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```


Restituisce o imposta il tempo di creazione di un commento. Impostare questa proprietà su java.util.Date(Long.MIN_VALUE) significa che non è impostato alcun tempo per il commento. Lettura/Scrittura java.util.Date.

--------------------

Il tempo del commento è un parametro opzionale.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```


Restituisce o imposta la diapositiva padre di un commento. Sola lettura [ISlide](../../com.aspose.slides/islide).

**Restituisce:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```


Restituisce l'autore di un commento. Sola lettura [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Restituisce:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract Point2D.Float getPosition()
```


Restituisce o imposta la posizione di un commento su una diapositiva. Lettura/Scrittura java.awt.geom.Point2D.Float.

**Restituisce:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public abstract void setPosition(Point2D.Float value)
```


Restituisce o imposta la posizione di un commento su una diapositiva. Lettura/Scrittura java.awt.geom.Point2D.Float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### remove() {#remove--}
```
public abstract void remove()
```


Rimuove il commento e tutte le sue risposte dalla raccolta padre.

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```


Ottiene o imposta il commento padre. Lettura/Scrittura [IComment](../../com.aspose.slides/icomment).

**Restituisce:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```


Ottiene o imposta il commento padre. Lettura/Scrittura [IComment](../../com.aspose.slides/icomment).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |