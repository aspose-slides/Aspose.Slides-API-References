---
title: CommentCollection
second_title: Référence API Aspose.Slides pour .NET
description: Représente une collection de commentaires d'un auteur.
type: docs
weight: 2560
url: /fr/aspose.slides/commentcollection/
---

## Classe CommentCollection

Représente une collection de commentaires d'un auteur.

```csharp
public sealed class CommentCollection : DomObject<CommentAuthor>, ICommentCollection
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../aspose.slides/commentcollection/count) { get; } | Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seule Int32. |
| [IsSynchronized](../../aspose.slides/commentcollection/issynchronized) { get; } | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (sécurisé pour les threads). Lecture seule Boolean. |
| [Item](../../aspose.slides/commentcollection/item) { get; } | Obtient l'élément à l'index spécifié. Lecture seule [`Comment`](../comment). |
| [SyncRoot](../../aspose.slides/commentcollection/syncroot) { get; } | Renvoie une racine de synchronisation. Lecture seule Object. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddComment](../../aspose.slides/commentcollection/addcomment)(string, ISlide, PointF, DateTime) | Ajoute un nouveau commentaire à la fin d'une collection. |
| [AddModernComment](../../aspose.slides/commentcollection/addmoderncomment)(string, ISlide, IShape, PointF, DateTime) | Ajoute un nouveau commentaire moderne à la fin d'une collection. |
| [Clear](../../aspose.slides/commentcollection/clear)() | Supprime tous les commentaires d'une collection. |
| [CopyTo](../../aspose.slides/commentcollection/copyto)(Array, int) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [FindCommentByIdx](../../aspose.slides/commentcollection/findcommentbyidx)(int) | Trouve un commentaire dans la collection par index. |
| [GetEnumerator](../../aspose.slides/commentcollection/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| [InsertComment](../../aspose.slides/commentcollection/insertcomment)(int, string, ISlide, PointF, DateTime) | Insère un nouveau commentaire dans une collection à l'index spécifié. |
| [InsertModernComment](../../aspose.slides/commentcollection/insertmoderncomment)(int, string, ISlide, IShape, PointF, DateTime) | Insère un nouveau commentaire moderne dans une collection à l'index spécifié. |
| [Remove](../../aspose.slides/commentcollection/remove)(IComment) | Supprime la première occurrence du commentaire spécifié dans une collection. |
| [RemoveAt](../../aspose.slides/commentcollection/removeat)(int) | Supprime l'élément à l'index spécifié dans une collection. |
| [ToArray](../../aspose.slides/commentcollection/toarray#toarray)() | Crée et renvoie un tableau avec tous les commentaires. |
| [ToArray](../../aspose.slides/commentcollection/toarray#toarray_1)(int, int) | Crée et renvoie un tableau avec tous les commentaires de la plage spécifiée. |

### Voir aussi

* classe [DomObject&lt;TParent&gt;](../domobject-1)
* classe [CommentAuthor](../commentauthor)
* interface [ICommentCollection](../icommentcollection)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- NE PAS ÉDITER : généré par xmldocmd pour Aspose.Slides.dll -->