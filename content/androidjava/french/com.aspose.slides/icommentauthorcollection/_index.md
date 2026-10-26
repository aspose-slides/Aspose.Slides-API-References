---
title: ICommentAuthorCollection
second_title: Aspose.Slides pour Android via la référence d'API Java
description: Représente une collection d'auteurs de commentaires.
type: docs
url: /fr/com.aspose.slides/icommentauthorcollection/
---
**Toutes les interfaces implémentées :**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

Représente une collection d'auteurs de commentaires.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Ajoute un nouvel auteur à la fin d'une collection. |
| [toArray()](#toArray--) | Crée et renvoie un tableau contenant tous les auteurs. |
| [findByName(String name)](#findByName-java.lang.String-) | Recherche un auteur dans une collection par nom. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Recherche un auteur dans une collection par nom et initiales. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'auteur à l'index spécifié de la collection. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Supprime la première occurrence de l'auteur spécifié dans une collection. |
| [clear()](#clear--) | Supprime tous les auteurs d'une collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```

Obtient l'élément à l'index spécifié. Lecture seule [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```

Ajoute un nouvel auteur à la fin d'une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom du nouvel auteur. |
| initials | java.lang.String | Initiales du nouvel auteur. |

**Renvoie :**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Nouvel objet [ICommentAuthor](../../com.aspose.slides/icommentauthor).
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```

Crée et renvoie un tableau contenant tous les auteurs.

**Renvoie :**
com.aspose.slides.ICommentAuthor[] - Tableau de [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```

Recherche un auteur dans une collection par nom.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom d'un auteur à rechercher. |

**Renvoie :**
com.aspose.slides.ICommentAuthor[] - Auteur ou null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

Recherche un auteur dans une collection par nom et initiales.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom d'un auteur à rechercher. |
| initials | java.lang.String | Initiales d'un auteur à rechercher. |

**Renvoie :**
com.aspose.slides.ICommentAuthor[] - Auteur ou null.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Supprime l'auteur à l'index spécifié de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à supprimer. |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```

Supprime la première occurrence de l'auteur spécifié dans une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | L'auteur à supprimer d'une collection. |
### clear() {#clear--}
```
public abstract void clear()
```

Supprime tous les auteurs d'une collection.