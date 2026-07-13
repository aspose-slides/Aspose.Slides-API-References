---
title: IComment
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a comment on a slide.
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
| [getCreatedTime()](#getCreatedTime--) | Retourneert of stelt de tijd van het maken van een opmerking in. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Retourneert of stelt de tijd van het maken van een opmerking in. |
| [getSlide()](#getSlide--) | Retourneert of stelt de bovenliggende dia van een opmerking in. |
| [getAuthor()](#getAuthor--) | Retourneert de auteur van een opmerking. |
| [getPosition()](#getPosition--) | Retourneert of stelt de positie van een opmerking op een dia in. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Retourneert of stelt de positie van een opmerking op een dia in. |
| [remove()](#remove--) | Verwijdert de opmerking en alle antwoorden ervan uit de bovenliggende verzameling. |
| [getParentComment()](#getParentComment--) | Haalt het bovenliggende commentaar op of stelt het in. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Haalt het bovenliggende commentaar op of stelt het in. |
### getText() {#getText--}
```
public abstract String getText()
```

Retourneert of stelt de platte tekst van een dia-opmerking in. Lezen/schrijven String.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Retourneert of stelt de platte tekst van een dia-opmerking in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Retourneert of stelt de tijd van het maken van een opmerking in. Het instellen van deze eigenschap op java.util.Date(Long.MIN_VALUE) betekent dat er geen opmerkingstijd is ingesteld. Lezen/schrijven java.util.Date.

--------------------

Opmerkingstijd is een optionele parameter.

**Returns:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Retourneert of stelt de tijd van het maken van een opmerking in. Het instellen van deze eigenschap op java.util.Date(Long.MIN_VALUE) betekent dat er geen opmerkingstijd is ingesteld. Lezen/schrijven java.util.Date.

--------------------

Opmerkingstijd is een optionele parameter.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```

Retourneert of stelt de bovenliggende dia van een opmerking in. Alleen-lezen [ISlide](../../com.aspose.slides/islide).

**Returns:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

Retourneert de auteur van een opmerking. Alleen-lezen [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Returns:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract PointF getPosition()
```

Retourneert of stelt de positie van een opmerking op een dia in. Lezen/schrijven android.graphics.PointF.

**Returns:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public abstract void setPosition(PointF value)
```

Retourneert of stelt de positie van een opmerking op een dia in. Lezen/schrijven android.graphics.PointF.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public abstract void remove()
```

Verwijdert de opmerking en alle antwoorden ervan uit de bovenliggende verzameling.

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

Haalt het bovenliggende commentaar op of stelt het in. Lezen/schrijven [IComment](../../com.aspose.slides/icomment).

**Returns:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

Haalt het bovenliggende commentaar op of stelt het in. Lezen/schrijven [IComment](../../com.aspose.slides/icomment).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |