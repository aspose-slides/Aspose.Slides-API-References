---
title: MasterSlideCollection
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une collection de diapositives principales.
type: docs
weight: 7360
url: /fr/net/aspose.slides/masterslidecollection/
---
## MasterSlideCollection class

Représente une collection de diapositives principales.

```csharp
public sealed class MasterSlideCollection : DomObject<Presentation>, IMasterSlideCollection
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Count](../../aspose.slides/masterslidecollection/count) { get; } | Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seuleInt32 . |
| [IsSynchronized](../../aspose.slides/masterslidecollection/issynchronized) { get; } | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seuleBoolean . |
| [Item](../../aspose.slides/masterslidecollection/item) { get; } | Obtient l'élément à l'index spécifié. Lecture seule[`MasterSlide`](../masterslide) . |
| [SyncRoot](../../aspose.slides/masterslidecollection/syncroot) { get; } | Renvoie une racine de synchronisation. Lecture seuleObject . |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddClone](../../aspose.slides/masterslidecollection/addclone)(IMasterSlide) | Ajoute une copie d'une diapositive principale spécifiée à la fin de la collection. Les diapositives de mise en page liées seront également copiées. |
| [CopyTo](../../aspose.slides/masterslidecollection/copyto)(Array, int) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [GetEnumerator](../../aspose.slides/masterslidecollection/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| [InsertClone](../../aspose.slides/masterslidecollection/insertclone)(int, IMasterSlide) | Insère une copie d'une diapositive principale spécifiée à la position spécifiée de la collection. Les diapositives de mise en page liées seront également copiées. |
| [Remove](../../aspose.slides/masterslidecollection/remove)(IMasterSlide) | Supprime la première occurrence d'un objet spécifique de la collection. |
| [RemoveAt](../../aspose.slides/masterslidecollection/removeat)(int) | Supprime l'élément à l'index spécifié de la collection. |
| [RemoveUnused](../../aspose.slides/masterslidecollection/removeunused)(bool) | Supprime les diapositives principales inutilisées. |

### Voir également

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [Presentation](../presentation)
* interface [IMasterSlideCollection](../imasterslidecollection)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->