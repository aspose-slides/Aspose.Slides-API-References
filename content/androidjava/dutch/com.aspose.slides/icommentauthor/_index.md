---
title: ICommentAuthor
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an author of comments.
type: docs
url: /nl/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

Stelt een auteur van opmerkingen voor.
## Methoden

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Returns or sets the author's name. |
| [setName(String value)](#setName-java.lang.String-) | Returns or sets the author's name. |
| [getInitials()](#getInitials--) | Returns or sets the authors initials. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Returns or sets the authors initials. |
| [getComments()](#getComments--) | Returns the collection of comments made by this author. |
| [remove()](#remove--) | Removes the author from the parent collection. |
### getName() {#getName--}
```
public abstract String getName()
```


Retourneert of stelt de naam van de auteur in. Lezen/Schrijven String.

**Retour:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Retourneert of stelt de naam van de auteur in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public abstract String getInitials()
```


Retourneert of stelt de initialen van de auteur in. Lezen/Schrijven String.

**Retour:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```


Retourneert of stelt de initialen van de auteur in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```


Retourneert de verzameling opmerkingen die door deze auteur zijn gemaakt. Alleen-lezen [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Retour:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```


Verwijdert de auteur uit de bovenliggende collectie.