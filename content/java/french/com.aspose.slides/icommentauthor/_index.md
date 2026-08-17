---
title: ICommentAuthor
second_title: Référence de l'API Aspose.Slides pour Java
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
| [getName()](#getName--) | Renvoie ou définit le nom de l'auteur. |
| [setName(String value)](#setName-java.lang.String-) | Renvoie ou définit le nom de l'auteur. |
| [getInitials()](#getInitials--) | Renvoie ou définit les initiales de l'auteur. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Renvoie ou définit les initiales de l'auteur. |
| [getComments()](#getComments--) | Renvoie la collection de commentaires créés par cet auteur. |
| [remove()](#remove--) | Supprime l'auteur de la collection parente. |
### getName() {#getName--}
```
public abstract String getName()
```

Renvoie ou définit le nom de l'auteur. Lecture/écriture String.

**Retour:**  
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Renvoie ou définit le nom de l'auteur. Lecture/écriture String.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public abstract String getInitials()
```

Renvoie ou définit les initiales de l'auteur. Lecture/écriture String.

**Retour:**  
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```

Renvoie ou définit les initiales de l'auteur. Lecture/écriture String.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```

Renvoie la collection de commentaires créés par cet auteur. Lecture seule [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Retour:**  
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```

Supprime l'auteur de la collection parente.