---
title: IComment
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a comment on a slide.
type: docs
url: /fr/com.aspose.slides/icomment/
---```
public interface IComment
```

Représente un commentaire sur une diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getText()](#getText--) | Renvoie ou définit le texte brut d'un commentaire de diapositive. |
| [setText(String value)](#setText-java.lang.String-) | Renvoie ou définit le texte brut d'un commentaire de diapositive. |
| [getCreatedTime()](#getCreatedTime--) | Renvoie ou définit l'heure de création d'un commentaire. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Renvoie ou définit l'heure de création d'un commentaire. |
| [getSlide()](#getSlide--) | Renvoie ou définit la diapositive parente d'un commentaire. |
| [getAuthor()](#getAuthor--) | Renvoie l'auteur d'un commentaire. |
| [getPosition()](#getPosition--) | Renvoie ou définit la position d'un commentaire sur une diapositive. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Renvoie ou définit la position d'un commentaire sur une diapositive. |
| [remove()](#remove--) | Supprime le commentaire et toutes ses réponses de la collection parente. |
| [getParentComment()](#getParentComment--) | Obtient ou définit le commentaire parent. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Obtient ou définit le commentaire parent. |
### getText() {#getText--}
```
public abstract String getText()
```

Renvoie ou définit le texte brut d'un commentaire de diapositive. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Renvoie ou définit le texte brut d'un commentaire de diapositive. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Renvoie ou définit l'heure de création d'un commentaire. Définir cette propriété sur java.util.Date(Long.MIN_VALUE) signifie qu'aucune heure de commentaire n'est définie. Lecture/écriture java.util.Date.

--------------------

Le temps du commentaire est un paramètre optionnel.

**Renvoie :**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Renvoie ou définit l'heure de création d'un commentaire. Définir cette propriété sur java.util.Date(Long.MIN_VALUE) signifie qu'aucune heure de commentaire n'est définie. Lecture/écriture java.util.Date.

--------------------

Le temps du commentaire est un paramètre optionnel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```

Renvoie ou définit la diapositive parente d'un commentaire. Lecture seule [ISlide](../../com.aspose.slides/islide).

**Renvoie :**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

Renvoie l'auteur d'un commentaire. Lecture seule [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Renvoie :**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract PointF getPosition()
```

Renvoie ou définit la position d'un commentaire sur une diapositive. Lecture/écriture android.graphics.PointF.

**Renvoie :**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public abstract void setPosition(PointF value)
```

Renvoie ou définit la position d'un commentaire sur une diapositive. Lecture/écriture android.graphics.PointF.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public abstract void remove()
```

Supprime le commentaire et toutes ses réponses de la collection parente.

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

Obtient ou définit le commentaire parent. Lecture/écriture [IComment](../../com.aspose.slides/icomment).

**Renvoie :**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

Obtient ou définit le commentaire parent. Lecture/écriture [IComment](../../com.aspose.slides/icomment).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |