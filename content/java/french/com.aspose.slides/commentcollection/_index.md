---
title: CommentCollection
second_title: Référence de l'API Aspose.Slides for Java
description: Représente une collection de commentaires d'un auteur.
type: docs
url: /fr/com.aspose.slides/commentcollection/
---
**Héritage :**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées :**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

Représente une collection de commentaires d'un auteur.

## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Obtient le nombre d'éléments réellement contenus dans la collection. |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Ajoute un nouveau commentaire à la fin d'une collection. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Ajoute un nouveau commentaire moderne à la fin d'une collection. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Insère un nouveau commentaire dans une collection à l'index spécifié. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Insère un nouveau commentaire moderne dans une collection à l'index spécifié. |
| [toArray()](#toArray--) | Crée et renvoie un tableau contenant tous les commentaires. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crée et renvoie un tableau contenant tous les commentaires de la plage spécifiée. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'élément à l'index spécifié dans une collection. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Supprime la première occurrence du commentaire spécifié dans une collection. |
| [clear()](#clear--) | Supprime tous les commentaires d'une collection. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Trouve un commentaire dans la collection par index. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |

### size() {#size--}
```
public final int size()
```

Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seule  int .

**Retourne :**
int

### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

Obtient l'élément à l'index spécifié. Lecture seule [Comment](../../com.aspose.slides/comment).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retourne :**
[IComment](../../com.aspose.slides/icomment)

### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Ajoute un nouveau commentaire à la fin d'une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte brut du nouveau commentaire. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositive de la présentation où ajouter le nouveau commentaire. |
| position | java.awt.geom.Point2D.Float | Position sur la diapositive où ajouter le nouveau commentaire. |
| creationTime | java.util.Date | Heure de création du commentaire. |

**Retourne :**
[IComment](../../com.aspose.slides/icomment) - Commentaire ajouté.

### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Ajoute un nouveau commentaire moderne à la fin d'une collection.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new Point2D.Float(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte brut du nouveau commentaire moderne. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositive de la présentation où ajouter le nouveau commentaire moderne. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forme sur la diapositive à laquelle le nouveau commentaire moderne est associé. |
| position | java.awt.geom.Point2D.Float | Position sur la diapositive où ajouter le nouveau commentaire moderne. |
| creationTime | java.util.Date | Heure de création du commentaire moderne. |

**Retourne :**
[IModernComment](../../com.aspose.slides/imoderncomment) - Commentaire moderne ajouté.

### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Insère un nouveau commentaire dans une collection à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de l'élément dans la collection où le commentaire doit être inséré. |
| text | java.lang.String | Texte brut du nouveau commentaire. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositive de la présentation où ajouter le nouveau commentaire. |
| position | java.awt.geom.Point2D.Float | Position sur la diapositive où ajouter le nouveau commentaire. |
| creationTime | java.util.Date | Heure de création du commentaire. |

**Retourne :**
[IComment](../../com.aspose.slides/icomment) - Commentaire inséré.

### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Insère un nouveau commentaire moderne dans une collection à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de l'élément dans la collection où le commentaire moderne doit être inséré. |
| text | java.lang.String | Texte brut du nouveau commentaire moderne. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositive de la présentation où ajouter le nouveau commentaire moderne. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forme sur la diapositive à laquelle le nouveau commentaire moderne est associé. |
| position | java.awt.geom.Point2D.Float | Position sur la diapositive où ajouter le nouveau commentaire moderne. |
| creationTime | java.util.Date | Heure de création du commentaire moderne. |

**Retourne :**
[IModernComment](../../com.aspose.slides/imoderncomment) - Commentaire moderne inséré.

### toArray() {#toArray--}
```
public final IComment[] toArray()
```

Crée et renvoie un tableau contenant tous les commentaires.

**Retourne :**
com.aspose.slides.IComment[] - Tableau de [Comment](../../com.aspose.slides/comment).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

Crée et renvoie un tableau contenant tous les commentaires de la plage spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | int | Index du premier commentaire à renvoyer. |
| count | int | Nombre de commentaires à renvoyer. |

**Retourne :**
com.aspose.slides.IComment[] - Tableau de [Comment](../../com.aspose.slides/comment).

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime l'élément à l'index spécifié dans une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à supprimer. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

Supprime la première occurrence du commentaire spécifié dans une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Le commentaire à supprimer de la collection. |

### clear() {#clear--}
```
public final void clear()
```

Supprime tous les commentaires d'une collection.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Retourne :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Un IGenericEnumerator utilisable pour parcourir la collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

Renvoie un itérateur java pour l'ensemble de la collection.

**Retourne :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Un java.util.Iterator pour l'ensemble de la collection.

### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

Trouve un commentaire dans la collection par index.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| idx | int | Index unique du commentaire à trouver  int . |

**Retourne :**
[IComment](../../com.aspose.slides/icomment) - Commentaire trouvé ou null [IComment](../../com.aspose.slides/icomment).

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copie tous les éléments de la collection dans le tableau spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau cible. |
| index | int | Index de départ dans le tableau cible. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule  boolean .

**Retourne :**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Renvoie une racine de synchronisation. Lecture seule  Object .

**Retourne :**
java.lang.Object