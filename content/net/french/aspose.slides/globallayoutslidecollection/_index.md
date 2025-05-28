---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slildes pour .NET Référence API
description: Représente une collection de toutes les diapositives de disposition dans la présentation. Étend la classe LayoutSlideCollection avec des méthodes pour ajouter/cloner des diapositives de disposition dans le contexte de l'union des collections individuelles de diapositives de maîtres de disposition.
type: docs
weight: 4780
url: /fr/aspose.slides/globallayoutslidecollection/
---

## Classe GlobalLayoutSlideCollection

Représente une collection de toutes les diapositives de disposition dans la présentation. Étend la classe LayoutSlideCollection avec des méthodes pour ajouter/cloner des diapositives de disposition dans le contexte de l'union des collections individuelles de diapositives de maîtres de disposition.

```csharp
public sealed class GlobalLayoutSlideCollection : LayoutSlideCollection, 
    IGlobalLayoutSlideCollection
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../aspose.slides/layoutslidecollection/count) { get; } | Renvoie le nombre de diapositives de disposition dans une collection. Lecture seule Int32. |
| [IsSynchronized](../../aspose.slides/layoutslidecollection/issynchronized) { get; } | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule Boolean. |
| [Item](../../aspose.slides/layoutslidecollection/item) { get; } | Renvoie la diapositive de disposition par index. Lecture seule [`LayoutSlide`](../layoutslide). |
| [SyncRoot](../../aspose.slides/layoutslidecollection/syncroot) { get; } | Renvoie une racine de synchronisation. Lecture seule Object. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../aspose.slides/globallayoutslidecollection/add)(IMasterSlide, SlideLayoutType, string) | Ajoute une nouvelle diapositive de disposition à la présentation. |
| [AddClone](../../aspose.slides/globallayoutslidecollection/addclone#addclone)(ILayoutSlide) | Ajoute une copie d'une diapositive de disposition spécifiée à la présentation. |
| [AddClone](../../aspose.slides/globallayoutslidecollection/addclone#addclone_1)(ILayoutSlide, IMasterSlide) | Ajoute une copie d'une diapositive de disposition spécifiée à la présentation. |
| [CopyTo](../../aspose.slides/layoutslidecollection/copyto)(Array, int) | Copie tous les éléments de la collection vers le tableau spécifié. |
| [GetByType](../../aspose.slides/layoutslidecollection/getbytype)(SlideLayoutType) | Renvoie la première diapositive de disposition du type spécifié. Un type de diapositive de disposition à trouver.[`LayoutSlide`](../layoutslide) avec type spécifié ou null si aucune disposition trouvée. |
| [GetEnumerator](../../aspose.slides/layoutslidecollection/getenumerator)() | Renvoie un énumérateur qui itère à travers la collection. |
| [Remove](../../aspose.slides/layoutslidecollection/remove)(ILayoutSlide) | Supprime une diapositive de la collection. |
| [RemoveUnused](../../aspose.slides/layoutslidecollection/removeunused)() | Supprime les diapositives de disposition non utilisées (diapositives de disposition dont HasDependingSlides est faux). |

### Voir Aussi

* classe [LayoutSlideCollection](../layoutslidecollection)
* interface [IGlobalLayoutSlideCollection](../igloballayoutslidecollection)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: généré par xmldocmd pour Aspose.Slides.dll -->