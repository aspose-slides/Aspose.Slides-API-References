---
title: ICommentCollection
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une collection de commentaires d'un auteur.
type: docs
url: /fr/com.aspose.slides/icommentcollection/
---
**Toutes les interfaces implémentées:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

Représente une collection de commentaires d'un auteur.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Ajoute un nouveau commentaire à la fin d'une collection. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Ajoute un nouveau commentaire moderne à la fin d'une collection. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Insère un nouveau commentaire dans une collection à l'index spécifié. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Insère un nouveau commentaire moderne dans une collection à l'index spécifié. |
| [toArray()](#toArray--) | Crée et renvoie un tableau contenant tous les commentaires. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crée et renvoie un tableau contenant les commentaires de la plage spécifiée. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'élément à l'index spécifié dans une collection. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Supprime la première occurrence du commentaire spécifié dans une collection. |
| [clear()](#clear--) | Supprime tous les commentaires d'une collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```


Obtient l'élément à l'index spécifié. Lecture seule [IComment](../../com.aspose.slides/icomment).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```


Ajoute un nouveau commentaire à la fin d'une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte brut d'un nouveau commentaire. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositive dans une présentation où ajouter un nouveau commentaire. |
| position | android.graphics.PointF | Position sur une diapositive où ajouter un nouveau commentaire. |
| creationTime | java.util.Date | Heure de création d'un commentaire. |

**Renvoie :**
[IComment](../../com.aspose.slides/icomment) - Commentaire ajouté.
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```


Ajoute un nouveau commentaire moderne à la fin d'une collection.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new android.graphics.PointF(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Plain text of a new modern comment. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide in a presentation where to add a new modern comment. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape on a slide to which a new modern comment is associated. |
| position | android.graphics.PointF | Position on a slide where to add a new modern comment. |
| creationTime | java.util.Date | Time of a modern comment creation. |

**Returns:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Added modern comment.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```


Insert new comment to a collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of the element in a collection at which comment should be inserted. |
| text | java.lang.String | Plain text of a new comment. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide in a presentation where to add a new comment. |
| position | android.graphics.PointF | Position on a slide where to add a new comment. |
| creationTime | java.util.Date | Time of a comment creation. |

**Returns:**
[IComment](../../com.aspose.slides/icomment) - Inserted comment.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Insert new modern comment to a collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of the element in a collection at which modern comment should be inserted. |
| text | java.lang.String | Plain text of a new modern comment. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide in a presentation where to add a new modern comment. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape on a slide to which a new modern comment is associated. |
| position | android.graphics.PointF | Position on a slide where to add a new modern comment. |
| creationTime | java.util.Date | Time of a modern comment creation. |

**Returns:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Inserted modern comment.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```

Creates and returns an array with all comments.

**Returns:**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```

Creates and returns an array with all comments from the specified range.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | An index of a first comment to return. |
| count | int | A number of comments to return. |

**Returns:**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Removes the element at the specified index in a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to remove. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```

Removes the first occurrence of the specified comment in a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | The comment to remove from a collection. |

### clear() {#clear--}
```
public abstract void clear()

Removes all comments from a collection.
