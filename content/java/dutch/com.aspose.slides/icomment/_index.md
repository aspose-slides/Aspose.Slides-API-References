---
title: IComment
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een opmerking op een dia voor.
type: docs
url: /nl/com.aspose.slides/icomment/
---```
public interface IComment
```

Stelt een opmerking op een dia voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getText()](#getText--) | Retourneert of stelt de platte tekst van een dia-opmerking in. |
| [setText(String value)](#setText-java.lang.String-) | Retourneert of stelt de platte tekst van een dia-opmerking in. |
| [getCreatedTime()](#getCreatedTime--) | Retourneert of stelt de tijd van het aanmaken van een opmerking in. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Retourneert of stelt de tijd van het aanmaken van een opmerking in. |
| [getSlide()](#getSlide--) | Retourneert of stelt de bovenliggende dia van een opmerking in. |
| [getAuthor()](#getAuthor--) | Retourneert de auteur van een opmerking. |
| [getPosition()](#getPosition--) | Retourneert of stelt de positie van een opmerking op een dia in. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | Retourneert of stelt de positie van een opmerking op een dia in. |
| [remove()](#remove--) | Verwijdert de opmerking en al haar antwoorden uit de bovenliggende collectie. |
| [getParentComment()](#getParentComment--) | Haalt op of stelt de bovenliggende opmerking in. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Haalt op of stelt de bovenliggende opmerking in. |
### getText() {#getText--}
```
public abstract String getText()
```

Retourneert of stelt de platte tekst van een dia-opmerking in. Lezen/Schrijven String.

**Retour:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Retourneert of stelt de platte tekst van een dia-opmerking in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Retourneert of stelt de tijd van het aanmaken van een opmerking in. Het instellen van deze eigenschap op java.util.Date(Long.MIN\_VALUE) betekent dat er geen tijd voor de opmerking is ingesteld. Lezen/Schrijven java.util.Date.

--------------------

Opmerkingstijd is een optionele parameter.

**Retour:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Retourneert of stelt de tijd van het aanmaken van een opmerking in. Het instellen van deze eigenschap op java.util.Date(Long.MIN\_VALUE) betekent dat er geen tijd voor de opmerking is ingesteld. Lezen/Schrijven java.util.Date.

--------------------

Opmerkingstijd is een optionele parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```

Retourneert of stelt de bovenliggende dia van een opmerking in. Alleen-lezen [ISlide](../../com.aspose.slides/islide).

**Retour:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

Retourneert de auteur van een opmerking. Alleen-lezen [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Retour:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract Point2D.Float getPosition()
```

Retourneert of stelt de positie van een opmerking op een dia in. Lezen/Schrijven java.awt.geom.Point2D.Float.

**Retour:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public abstract void setPosition(Point2D.Float value)
```

Retourneert of stelt de positie van een opmerking op een dia in. Lezen/Schrijven java.awt.geom.Point2D.Float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### remove() {#remove--}
```
public abstract void remove()
```

Verwijdert de opmerking en al haar antwoorden uit de bovenliggende collectie.

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

Haalt op of stelt de bovenliggende opmerking in. Lezen/Schrijven [IComment](../../com.aspose.slides/icomment).

**Retour:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

Haalt op of stelt de bovenliggende opmerking in. Lezen/Schrijven [IComment](../../com.aspose.slides/icomment).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |