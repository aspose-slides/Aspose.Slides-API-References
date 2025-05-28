---
title: SlideCollection
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une collection de diapositives.
type: docs
weight: 9220
url: /fr/aspose.slides/slidecollection/
---
## SlideCollection class

Représente une collection de diapositives.

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seuleInt32 . |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seuleBoolean . |
| [Item](../../aspose.slides/slidecollection/item) { get; } | Obtient l'élément à l'index spécifié. Lecture seule[`Slide`](../slide) . |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | Renvoie une racine de synchronisation. Lecture seuleObject . |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | Ajoute une copie d'une diapositive spécifiée à la fin de la collection. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Ajoute une copie d'une diapositive spécifiée à la fin de la collection. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | Ajoute une copie d'une diapositive spécifiée à la fin de la section spécifiée. |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Ajoute une copie d'une diapositive source spécifiée à la fin de la collection. La mise en page appropriée sera sélectionnée automatiquement à partir du maître spécifié (la mise en page appropriée est la mise en page avec le même type ou nom que de mise en page de la diapositive source). S'il n'y a pas de disposition appropriée, la disposition de la diapositive source sera clonée (si allowCloneMissingLayout est vrai) ou PptxEditException sera levée (si allowCloneMissingLayout est faux). |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | Ajoute une nouvelle diapositive vide à la fin de la collection. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection. |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection. |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(string) | Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection. |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | Renvoie un index de la diapositive spécifiée dans la collection. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | Insère une copie d'une diapositive spécifiée à la position spécifiée de la collection. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Insère une copie d'une diapositive spécifiée à la position spécifiée de la collection. |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Insère une copie d'une diapositive source spécifiée à la position spécifiée de la collection. La mise en page appropriée sera sélectionnée automatiquement à partir du maître spécifié (la mise en page appropriée est la mise en page avec le même type ou nom que de mise en page de la diapositive source). S'il n'y a pas de disposition appropriée, la disposition de la diapositive source sera clonée (si allowCloneMissingLayout est vrai) ou PptxEditException sera levée (si allowCloneMissingLayout est faux). |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | Insère une copie d'une diapositive spécifiée à la position spécifiée de la collection. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, string) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, TextReader) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, string, IExternalResourceResolver, string) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée. |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, TextReader, IExternalResourceResolver, string) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée. |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | Supprime la première occurrence d'un objet spécifique de la collection. |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | Supprime l'élément à l'index spécifié de la collection. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | Déplace la diapositive de la collection vers la position spécifiée. |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | Déplace les diapositives de la collection vers la position spécifiée. Les diapositives seront placées à partir de l'index dans l'ordre dans lequel elles apparaissent dans la liste. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | Crée et renvoie un tableau contenant toutes les diapositives. |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | Crée et renvoie un tableau contenant toutes les diapositives de la plage spécifiée. Un index d'une première diapositive à ajouter.Un certain nombre de diapositives à ajouter. |

### Voir également

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [Presentation](../presentation)
* interface [ISlideCollection](../islidecollection)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
