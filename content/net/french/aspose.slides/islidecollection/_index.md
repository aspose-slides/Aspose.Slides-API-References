---
title: ISlideCollection
second_title: Aspose.Sildes pour la référence API .NET
description: Représente une collection de diapositives.
type: docs
weight: 6830
url: /fr/aspose.slides/islidecollection/
---

## Interface ISlideCollection

Représente une collection de diapositives.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Obtient l'élément à l'index spécifié. Lecture seule [`ISlide`](../islide). |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Ajoute une copie d'une diapositive spécifiée à la fin de la collection. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Ajoute une copie d'une diapositive spécifiée à la fin de la collection. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Ajoute une copie d'une diapositive spécifiée à la fin de la section spécifiée. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Ajoute une copie d'une diapositive source spécifiée à la fin de la collection. La mise en page appropriée sera sélectionnée automatiquement à partir du maître spécifié (la mise en page appropriée est la mise en page ayant le même Type ou Nom que celle de la diapositive source). S'il n'y a pas de mise en page appropriée, alors la mise en page de la diapositive source sera clonée (si allowCloneMissingLayout est vrai) ou une PptxEditException sera levée (si allowCloneMissingLayout est faux). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Ajoute une nouvelle diapositive vide à la fin de la collection. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection en tenant compte des options d'importation PDF. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Renvoie un index de la diapositive spécifiée dans la collection. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Insère une copie d'une diapositive spécifiée à la position spécifiée de la collection. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Insère une copie d'une diapositive spécifiée à la position spécifiée de la collection. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Insère une copie d'une diapositive source spécifiée à la position spécifiée de la collection. La mise en page appropriée sera sélectionnée automatiquement à partir du maître spécifié (la mise en page appropriée est la mise en page ayant le même Type ou Nom que celle de la diapositive source). S'il n'y a pas de mise en page appropriée, alors la mise en page de la diapositive source sera clonée (si allowCloneMissingLayout est vrai) ou une PptxEditException sera levée (si allowCloneMissingLayout est faux). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Insère une copie d'une diapositive spécifiée à la position spécifiée de la collection. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position spécifiée. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Supprime la première occurrence d'un objet spécifique de la collection. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Supprime l'élément à l'index spécifié de la collection. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Déplace la diapositive de la collection vers la position spécifiée. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Déplace les diapositives de la collection vers la position spécifiée. Les diapositives seront placées à partir de l'index dans l'ordre dans lequel elles apparaissent dans la liste. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Crée et renvoie un tableau contenant toutes les diapositives. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Crée et renvoie un tableau contenant toutes les diapositives d'une plage spécifiée. |

### Voir aussi

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [ISlide](../islide)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->