---
title: ICommentCollection
second_title: Référence de l'API Aspose.Slides pour Java
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
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Ajoute un nouveau commentaire à la fin d'une collection. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Ajoute un nouveau commentaire moderne à la fin d'une collection. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Insère un nouveau commentaire dans une collection à l'index spécifié. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Insère un nouveau commentaire moderne dans une collection à l'index spécifié. |
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

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```


Ajoute un nouveau commentaire à la fin d'une collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte brut d'un nouveau commentaire. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositive dans une présentation où ajouter le nouveau commentaire. |
| position | java.awt.geom.Point2D.Float | Position sur une diapositive où ajouter le nouveau commentaire. |
| creationTime | java.util.Date | Heure de création du commentaire. |

**Retour:**
[IComment](../../com.aspose.slides/icomment) - Commentaire ajouté.
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
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


**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Texte brut d'un nouveau commentaire moderne. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositive dans une présentation où ajouter le nouveau commentaire moderne. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forme sur une diapositive à laquelle un nouveau commentaire moderne est associé. |
| position | java.awt.geom.Point2D.Float | Position sur une diapositive où ajouter le nouveau commentaire moderne. |
| creationTime | java.util.Date | Heure de création du commentaire moderne. |

**Retour:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Commentaire moderne ajouté.
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```


Insère un nouveau commentaire dans une collection à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de l'élément dans une collection où le commentaire doit être inséré. |
| text | java.lang.String | Texte brut d'un nouveau commentaire. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositive dans une présentation où ajouter le nouveau commentaire. |
| position | java.awt.geom.Point2D.Float | Position sur une diapositive où ajouter le nouveau commentaire. |
| creationTime | java.util.Date | Heure de création du commentaire. |

**Retour:**
[IComment](../../com.aspose.slides/icomment) - Commentaire inséré.
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```


Insère un nouveau commentaire moderne dans une collection à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de l'élément dans une collection où le commentaire moderne doit être inséré. |
| text | java.lang.String | Texte brut d'un nouveau commentaire moderne. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositive dans une présentation où ajouter le nouveau commentaire moderne. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forme sur une diapositive à laquelle un nouveau commentaire moderne est associé. |
| position | java.awt.geom.Point2D.Float | Position sur une diapositive où ajouter le nouveau commentaire moderne. |
| creationTime | java.util.Date | Heure de création du commentaire moderne. |

**Retour:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Commentaire moderne inséré.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```


Crée et renvoie un tableau contenant tous les commentaires.

**Retour:**
com.aspose.slides.IComment[] - Tableau de [IComment](../../com.aspose.slides/icomment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```


Crée et renvoie un tableau contenant les commentaires de la plage spécifiée.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | int | Index du premier commentaire à renvoyer. |
| count | int | Nombre de commentaires à renvoyer. |

**Retour:**
com.aspose.slides.IComment[] - Tableau de [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Supprime l'élément à l'index spécifié dans une collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à supprimer. |
### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```


Supprime la première occurrence du commentaire spécifié dans une collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Le commentaire à supprimer d'une collection. |
### clear() {#clear--}
```
public abstract void clear()
```


Supprime tous les commentaires d'une collection.