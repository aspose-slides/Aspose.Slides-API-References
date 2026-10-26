---
title: ICommentAuthor
second_title: Aspose.Slides for Android via Java API Reference
description: Représente un auteur de commentaires.
type: docs
url: /fr/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

Représente un auteur de commentaires.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getName()](#getName--) | Retourne ou définit le nom de l'auteur. |
| [setName(String value)](#setName-java.lang.String-) | Retourne ou définit le nom de l'auteur. |
| [getInitials()](#getInitials--) | Retourne ou définit les initiales de l'auteur. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Retourne ou définit les initiales de l'auteur. |
| [getComments()](#getComments--) | Retourne la collection des commentaires faits par cet auteur. |
| [remove()](#remove--) | Supprime l'auteur de la collection parent. |
### getName() {#getName--}
```
public abstract String getName()
```

Retourne ou définit le nom de l'auteur. Lecture/écriture String.

**Retour:**  
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Retourne ou définit le nom de l'auteur. Lecture/écriture String.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public abstract String getInitials()
```

Retourne ou définit les initiales de l'auteur. Lecture/écriture String.

**Retour:**  
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```

Retourne ou définit les initiales de l'auteur. Lecture/écriture String.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```

Retourne la collection des commentaires faits par cet auteur. Lecture seule [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Retour:**  
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```

Supprime l'auteur de la collection parent.