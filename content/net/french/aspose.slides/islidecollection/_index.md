---
title: ISlideCollection
second_title: Aspose.Sildes pour .NET Référence de l'API
description: Représente une collection de diapositives.
type: docs
weight: 7050
url: /fr/aspose.slides/islidecollection/
---
## ISlideCollection interface

Représente une collection de diapositives.

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | Obtient l'élément à l'index spécifié. Lecture seule [`ISlide`](../islide). |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | Ajoute une copie d'une diapositive spécifiée à la fin de la collection. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | Ajoute une copie d'une diapositive spécifiée à la fin de la collection. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | Ajoute une copie d'une diapositive spécifiée à la fin de la section spécifiée. |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | Ajoute une copie d'une diapositive source spécifiée à la fin de la collection. La disposition appropriée sera sélectionnée automatiquement à partir du maître spécifié (la disposition appropriée est la disposition ayant le même Type ou le même Nom que la disposition de la diapositive source). S'il n'existe aucune disposition appropriée, la disposition de la diapositive source sera clonée (si allowCloneMissingLayout est vrai) ou une PptxEditException sera levée (si allowCloneMissingLayout est faux). |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | Ajoute une nouvelle diapositive vide à la fin de la collection. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection. |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | Crée des diapositives à partir de texte HTML et les ajoute à la fin de la collection. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection. |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection en tenant compte des options d'importation pdf. |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | Renvoie l'index de la diapositive spécifiée dans la collection. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | Insère une copie d'une diapositive spécifiée à la position indiquée de la collection. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | Insère une copie d'une diapositive spécifiée à la position indiquée de la collection. |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | Insère une copie d'une diapositive source spécifiée à la position indiquée de la collection. La disposition appropriée sera sélectionnée automatiquement à partir du maître spécifié (la disposition appropriée est la disposition ayant le même Type ou le même Nom que la disposition de la diapositive source). S'il n'existe aucune disposition appropriée, la disposition de la diapositive source sera clonée (si allowCloneMissingLayout est vrai) ou une PptxEditException sera levée (si allowCloneMissingLayout est faux). |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | Insère une copie d'une diapositive spécifiée à la position indiquée de la collection. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position indiquée. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position indiquée. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position indiquée. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position indiquée. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position indiquée. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position indiquée. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position indiquée. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position indiquée. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position indiquée. |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | Crée des diapositives à partir de texte HTML et les insère dans la collection à la position indiquée. |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | Supprime la première occurrence d'un objet spécifique de la collection. |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | Supprime l'élément à l'index spécifié de la collection. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | Déplace la diapositive de la collection vers la position indiquée. |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | Déplace les diapositives de la collection vers la position indiquée. Les diapositives seront placées à partir de l'index dans l'ordre où elles apparaissent dans la liste. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | Crée et renvoie un tableau contenant toutes les diapositives. |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | Crée et renvoie un tableau contenant toutes les diapositives de la plage spécifiée. |

### Voir aussi

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [ISlide](../islide)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->