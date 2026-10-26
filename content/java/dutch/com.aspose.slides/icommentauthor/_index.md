---
title: ICommentAuthor
second_title: Aspose.Slides for Java API Reference
description: Stelt een auteur van opmerkingen voor.
type: docs
url: /nl/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

Stelt een auteur van opmerkingen voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getName()](#getName--) | Geeft de naam van de auteur terug of stelt deze in. |
| [setName(String value)](#setName-java.lang.String-) | Geeft de naam van de auteur terug of stelt deze in. |
| [getInitials()](#getInitials--) | Geeft de initialen van de auteur terug of stelt deze in. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Geeft de initialen van de auteur terug of stelt deze in. |
| [getComments()](#getComments--) | Geeft de collectie van door deze auteur gemaakte opmerkingen terug. |
| [remove()](#remove--) | Verwijdert de auteur uit de bovenliggende collectie. |
### getName() {#getName--}
```
public abstract String getName()
```


Geeft de naam van de auteur terug of stelt deze in. Lezen/Schrijven String.

**Retour:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Geeft de naam van de auteur terug of stelt deze in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getInitials() {#getInitials--}
```
public abstract String getInitials()
```


Geeft de initialen van de auteur terug of stelt deze in. Lezen/Schrijven String.

**Retour:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```


Geeft de initialen van de auteur terug of stelt deze in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```


Geeft de collectie van door deze auteur gemaakte opmerkingen terug. Alleen-lezen [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Retour:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```


Verwijdert de auteur uit de bovenliggende collectie.