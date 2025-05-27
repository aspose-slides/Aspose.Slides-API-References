---
title: ICell
second_title: Référence API Aspose.Slides pour .NET
description: Représente une cellule dans un tableau.
type: docs
weight: 5250
url: /fr/aspose.slides/icell/
---

## Interface ICell

Représente une cellule dans un tableau.

```csharp
public interface ICell : ISlideComponent
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AnchorCenter](../../aspose.slides/icell/anchorcenter) { get; set; } | Détermine si le texte est centré à l'intérieur d'une cellule. Booléen lisible/écrivible. |
| [AsISlideComponent](../../aspose.slides/icell/asislidecomponent) { get; } | Permet d'obtenir l'interface de base ISlideComponent. Lecture seule [`ISlideComponent`](../islidecomponent). |
| [CellFormat](../../aspose.slides/icell/cellformat) { get; } | Renvoie l'objet CellFormat qui contient les propriétés de formatage pour cette cellule. Lecture seule [`ICellFormat`](../icellformat). |
| [ColSpan](../../aspose.slides/icell/colspan) { get; } | Renvoie le nombre de colonnes de grille dans la grille du tableau parent qui seront couvertes par la cellule actuelle. Cette propriété permet aux cellules d'avoir l'apparence d'être fusionnées, car elles s'étendent sur les limites verticales des autres cellules dans le tableau. Lecture seule Int32. |
| [FirstColumn](../../aspose.slides/icell/firstcolumn) { get; } | Obtient la première colonne de la cellule. Lecture seule [`IColumn`](../icolumn). |
| [FirstColumnIndex](../../aspose.slides/icell/firstcolumnindex) { get; } | Renvoie l'index de la première colonne, couverte par la cellule. Lecture seule Int32. |
| [FirstRow](../../aspose.slides/icell/firstrow) { get; } | Obtient la première ligne de la cellule. Lecture seule [`IRow`](../irow). |
| [FirstRowIndex](../../aspose.slides/icell/firstrowindex) { get; } | Renvoie l'index de la première ligne, couverte par la cellule. Lecture seule Int32. |
| [Height](../../aspose.slides/icell/height) { get; } | Renvoie la hauteur de la cellule. Lecture seule Double. |
| [IsMergedCell](../../aspose.slides/icell/ismergedcell) { get; } | Renvoie true si la cellule est fusionnée avec une autre cellule ajustée, false sinon. Lecture seule Booléen. |
| [MarginBottom](../../aspose.slides/icell/marginbottom) { get; set; } | Renvoie ou définit la marge inférieure dans un TextFrame. Lisible/écrivible Double. |
| [MarginLeft](../../aspose.slides/icell/marginleft) { get; set; } | Renvoie ou définit la marge gauche dans un TextFrame. Lisible/écrivible Double. |
| [MarginRight](../../aspose.slides/icell/marginright) { get; set; } | Renvoie ou définit la marge droite dans un TextFrame. Lisible/écrivible Double. |
| [MarginTop](../../aspose.slides/icell/margintop) { get; set; } | Renvoie ou définit la marge supérieure dans un TextFrame. Lisible/écrivible Double. |
| [MinimalHeight](../../aspose.slides/icell/minimalheight) { get; } | Renvoie la hauteur minimale d'une cellule. C'est la somme des hauteurs minimales de toutes les lignes couvertes par la cellule. Lecture seule Double. |
| [OffsetX](../../aspose.slides/icell/offsetx) { get; } | Renvoie la distance du côté gauche d'un tableau au côté gauche d'une cellule. Lecture seule Double. |
| [OffsetY](../../aspose.slides/icell/offsety) { get; } | Renvoie la distance du côté supérieur d'un tableau au côté supérieur d'une cellule. Lecture seule Double. |
| [RowSpan](../../aspose.slides/icell/rowspan) { get; } | Renvoie le nombre de lignes qu'une cellule fusionnée couvre. Cela est utilisé en combinaison avec l'attribut vMerge sur d'autres cellules afin de spécifier la cellule de début d'une fusion horizontale. Lecture seule Int32. |
| [Table](../../aspose.slides/icell/table) { get; } | Renvoie l'objet Table parent pour une cellule. Lecture seule [`ITable`](../itable). |
| [TextAnchorType](../../aspose.slides/icell/textanchortype) { get; set; } | Renvoie ou définit le type d'ancre de texte. Lisible/écrivible [`TextAnchorType`](../textanchortype). |
| [TextFrame](../../aspose.slides/icell/textframe) { get; } | Renvoie le cadre de texte d'une cellule. Lecture seule [`ITextFrame`](../itextframe). |
| [TextVerticalType](../../aspose.slides/icell/textverticaltype) { get; set; } | Renvoie ou définit le type de texte vertical. Lisible/écrivible [`TextVerticalType`](../textverticaltype). |
| [Width](../../aspose.slides/icell/width) { get; } | Renvoie la largeur de la cellule. Lecture seule Double. |

## Méthodes

| Nom | Description |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/icell/splitbycolspan)(int) | Divise la cellule en deux cellules par index de colonne. |
| [SplitByHeight](../../aspose.slides/icell/splitbyheight)(double) | Divise la cellule par hauteur. |
| [SplitByRowSpan](../../aspose.slides/icell/splitbyrowspan)(int) | Divise la cellule en deux cellules par index de ligne. |
| [SplitByWidth](../../aspose.slides/icell/splitbywidth)(double) | Divise la cellule par largeur. |

### Voir aussi

* interface [ISlideComponent](../islidecomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->