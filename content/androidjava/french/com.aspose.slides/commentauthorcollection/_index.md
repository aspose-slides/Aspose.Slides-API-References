---
title: CommentAuthorCollection
second_title: Référence API Java pour Aspose.Slides pour Android
description: Représente une collection d'auteurs de commentaires.
type: docs
url: /fr/com.aspose.slides/commentauthorcollection/
---
**Héritage:**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées:**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

Représente une collection d'auteurs de commentaires.
## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Renvoie le nombre d'éléments réellement contenus dans la collection. |
| [get_Item(int index)](#get-Item-int-) | Renvoie l'élément à l'index spécifié. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Ajoute un nouvel auteur à la fin d'une collection. |
| [toArray()](#toArray--) | Crée et renvoie un tableau contenant tous les auteurs. |
| [findByName(String name)](#findByName-java.lang.String-) | Recherche un auteur dans une collection par nom. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Recherche un auteur dans une collection par nom et initiales. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'auteur à l'index spécifié de la collection. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Supprime la première occurrence de l'auteur spécifié dans une collection. |
| [clear()](#clear--) | Supprime tous les auteurs d'une collection. |
| [iterator()](#iterator--) | Renvoie un itérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |
### size() {#size--}
```
public final int size()
```

Renvoie le nombre d'éléments réellement contenus dans la collection. Lecture seule int.

**Renvoie:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```

Renvoie l'élément à l'index spécifié. Lecture seule [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```

Ajoute un nouvel auteur à la fin d'une collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom du nouvel auteur. |
| initials | java.lang.String | Initiales du nouvel auteur. |

**Renvoie:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Nouveau [ICommentAuthor](../../com.aspose.slides/icommentauthor) objet.
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```

Crée et renvoie un tableau contenant tous les auteurs.

**Renvoie:**
com.aspose.slides.ICommentAuthor[] - Tableau de [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```

Recherche un auteur dans une collection par nom.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de l'auteur à rechercher. |

**Renvoie:**
com.aspose.slides.ICommentAuthor[] - Auteur ou null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

Recherche un auteur dans une collection par nom et initiales.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de l'auteur à rechercher. |
| initials | java.lang.String | Initiales de l'auteur à rechercher. |

**Renvoie:**
com.aspose.slides.ICommentAuthor[] - Auteur ou null.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime l'auteur à l'index spécifié de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index zéro-based de l'élément à supprimer. |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```

Supprime la première occurrence de l'auteur spécifié dans une collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | L'auteur à supprimer de la collection. |
### clear() {#clear--}
```
public final void clear()
```

Supprime tous les auteurs d'une collection.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```

Renvoie un itérateur qui parcourt la collection.

**Renvoie:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```

Renvoie un itérateur java pour l'ensemble de la collection.

**Renvoie:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Un java.util.Iterator pour l'ensemble de la collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copie tous les éléments de la collection dans le tableau spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau cible. |
| index | int | Index de départ dans le tableau cible. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule boolean.

**Renvoie:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Renvoie une racine de synchronisation. Lecture seule Object.

**Renvoie:**
java.lang.Object