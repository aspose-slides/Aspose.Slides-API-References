---
title: IComment
second_title: Aspose.Slides for Java API Reference
description: Představuje komentář na snímku.
type: docs
url: /cs/com.aspose.slides/icomment/
---```
public interface IComment
```

Představuje komentář na snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getText()](#getText--) | Vrací nebo nastavuje prostý text komentáře snímku. |
| [setText(String value)](#setText-java.lang.String-) | Vrací nebo nastavuje prostý text komentáře snímku. |
| [getCreatedTime()](#getCreatedTime--) | Vrací nebo nastavuje čas vytvoření komentáře. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Vrací nebo nastavuje čas vytvoření komentáře. |
| [getSlide()](#getSlide--) | Vrací nebo nastavuje nadřazený snímek komentáře. |
| [getAuthor()](#getAuthor--) | Vrací autora komentáře. |
| [getPosition()](#getPosition--) | Vrací nebo nastavuje polohu komentáře na snímku. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | Vrací nebo nastavuje polohu komentáře na snímku. |
| [remove()](#remove--) | Odstraňuje komentář a všechny jeho odpovědi z nadřazené kolekce. |
| [getParentComment()](#getParentComment--) | Získává nebo nastavuje nadřazený komentář. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Získává nebo nastavuje nadřazený komentář. |
### getText() {#getText--}
```
public abstract String getText()
```


Vrací nebo nastavuje prostý text komentáře snímku. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Vrací nebo nastavuje prostý text komentáře snímku. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```


Vrací nebo nastavuje čas vytvoření komentáře. Nastavení této vlastnosti na java.util.Date(Long.MIN\_VALUE) znamená, že není nastaven čas komentáře. Čtení/Zápis java.util.Date.

--------------------

Čas komentáře je volitelný parametr.

**Vrací:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```


Vrací nebo nastavuje čas vytvoření komentáře. Nastavení této vlastnosti na java.util.Date(Long.MIN\_VALUE) znamená, že není nastaven čas komentáře. Čtení/Zápis java.util.Date.

--------------------

Čas komentáře je volitelný parametr.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```


Vrací nebo nastavuje nadřazený snímek komentáře. Pouze ke čtení [ISlide](../../com.aspose.slides/islide).

**Vrací:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```


Vrací autora komentáře. Pouze ke čtení [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Vrací:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract Point2D.Float getPosition()
```


Vrací nebo nastavuje polohu komentáře na snímku. Čtení/Zápis java.awt.geom.Point2D.Float.

**Vrací:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public abstract void setPosition(Point2D.Float value)
```


Vrací nebo nastavuje polohu komentáře na snímku. Čtení/Zápis java.awt.geom.Point2D.Float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### remove() {#remove--}
```
public abstract void remove()
```


Odstraňuje komentář a všechny jeho odpovědi z nadřazené kolekce.

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```


Vrací nebo nastavuje nadřazený komentář. Čtení/Zápis [IComment](../../com.aspose.slides/icomment).

**Vrací:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```


Vrací nebo nastavuje nadřazený komentář. Čtení/Zápis [IComment](../../com.aspose.slides/icomment).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |