---
title: ICommentCollection
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une collection de commentaires dun auteur.
type: docs
weight: 5120
url: /fr/net/aspose.slides/icommentcollection/
---
## ICommentCollection interface

Représente une collection de commentaires d'un auteur.

```csharp
public interface ICommentCollection : IGenericCollection<IComment>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Item](../../aspose.slides/icommentcollection/item) { get; } | Obtient l'élément à l'index spécifié. Lecture seule[`IComment`](../icomment) . |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddComment](../../aspose.slides/icommentcollection/addcomment)(string, ISlide, PointF, DateTime) | Ajouter un nouveau commentaire à la fin d'une collection. |
| [AddModernComment](../../aspose.slides/icommentcollection/addmoderncomment)(string, ISlide, IShape, PointF, DateTime) | Ajouter un nouveau commentaire moderne à la fin d'une collection. |
| [Clear](../../aspose.slides/icommentcollection/clear)() | Supprime tous les commentaires d'une collection. |
| [InsertComment](../../aspose.slides/icommentcollection/insertcomment)(int, string, ISlide, PointF, DateTime) | Insérer un nouveau commentaire dans une collection à l'index spécifié. |
| [InsertModernComment](../../aspose.slides/icommentcollection/insertmoderncomment)(int, string, ISlide, IShape, PointF, DateTime) | Insérer un nouveau commentaire moderne dans une collection à l'index spécifié. |
| [Remove](../../aspose.slides/icommentcollection/remove)(IComment) | Supprime la première occurrence du commentaire spécifié dans une collection. |
| [RemoveAt](../../aspose.slides/icommentcollection/removeat)(int) | Supprime l'élément à l'index spécifié dans une collection. |
| [ToArray](../../aspose.slides/icommentcollection/toarray#toarray)() | Crée et renvoie un tableau avec tous les commentaires. |
| [ToArray](../../aspose.slides/icommentcollection/toarray#toarray_1)(int, int) | Crée et renvoie un tableau avec tous les commentaires de la plage spécifiée. |

### Voir également

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [IComment](../icomment)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->