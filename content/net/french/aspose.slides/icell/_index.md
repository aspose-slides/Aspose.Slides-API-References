---
title: ICell
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Représente une cellule dans un tableau.
type: docs
weight: 5450
url: /fr/aspose.slides/icell/
---
## ICell interface

Représente une cellule dans un tableau.

```csharp
public interface ICell : ISlideComponent
```

## Propriétés

| Name | Description |
| --- | --- |
| [AnchorCenter](../../aspose.slides/icell/anchorcenter) { get; set; } | Détermine si la zone de texte est centrée à l'intérieur d'une cellule. Lecture/écriture Boolean. |
| [AsISlideComponent](../../aspose.slides/icell/asislidecomponent) { get; } | Permet d'obtenir l'interface de base ISlideComponent. Lecture seule [`ISlideComponent`](../islidecomponent). |
| [CellFormat](../../aspose.slides/icell/cellformat) { get; } | Renvoie l'objet CellFormat qui contient les propriétés de mise en forme de cette cellule. Lecture seule [`ICellFormat`](../icellformat). |
| [ColSpan](../../aspose.slides/icell/colspan) { get; } | Renvoie le nombre de colonnes de la grille du tableau parent qui doivent être couvertes par la cellule actuelle. Cette propriété permet aux cellules d'avoir l'apparence d'être fusionnées, car elles s'étendent sur les limites verticales d'autres cellules du tableau. Lecture seule Int32. |
| [FirstColumn](../../aspose.slides/icell/firstcolumn) { get; } | Obtient la première colonne de la cellule. Lecture seule [`IColumn`](../icolumn). |
| [FirstColumnIndex](../../aspose.slides/icell/firstcolumnindex) { get; } | Renvoie l'index de la première colonne couverte par la cellule. Lecture seule Int32. |
| [FirstRow](../../aspose.slides/icell/firstrow) { get; } | Obtient la première ligne de la cellule. Lecture seule [`IRow`](../irow). |
| [FirstRowIndex](../../aspose.slides/icell/firstrowindex) { get; } | Renvoie l'index de la première ligne couverte par la cellule. Lecture seule Int32. |
| [Height](../../aspose.slides/icell/height) { get; } | Renvoie la hauteur de la cellule. Lecture seule Double. |
| [IsMergedCell](../../aspose.slides/icell/ismergedcell) { get; } | Renvoie true si la cellule est fusionnée avec une cellule adjacente, false sinon. Lecture seule Boolean. |
| [MarginBottom](../../aspose.slides/icell/marginbottom) { get; set; } | Renvoie ou définit la marge inférieure dans un TextFrame. Lecture/écriture Double. |
| [MarginLeft](../../aspose.slides/icell/marginleft) { get; set; } | Renvoie ou définit la marge gauche dans un TextFrame. Lecture/écriture Double. |
| [MarginRight](../../aspose.slides/icell/marginright) { get; set; } | Renvoie ou définit la marge droite dans un TextFrame. Lecture/écriture Double. |
| [MarginTop](../../aspose.slides/icell/margintop) { get; set; } | Renvoie ou définit la marge supérieure dans un TextFrame. Lecture/écriture Double. |
| [MinimalHeight](../../aspose.slides/icell/minimalheight) { get; } | Renvoie la hauteur minimale d'une cellule. Il s'agit de la somme des hauteurs minimales de toutes les lignes couvertes par la cellule. Lecture seule Double. |
| [OffsetX](../../aspose.slides/icell/offsetx) { get; } | Renvoie la distance du côté gauche du tableau au côté gauche de la cellule. Lecture seule Double. |
| [OffsetY](../../aspose.slides/icell/offsety) { get; } | Renvoie la distance du côté supérieur du tableau au côté supérieur de la cellule. Lecture seule Double. |
| [RowSpan](../../aspose.slides/icell/rowspan) { get; } | Renvoie le nombre de lignes qu'une cellule fusionnée occupe. Ceci est utilisé en combinaison avec l'attribut vMerge sur d'autres cellules afin de spécifier la cellule de départ d'une fusion horizontale. Lecture seule Int32. |
| [Table](../../aspose.slides/icell/table) { get; } | Renvoie l'objet Table parent de la cellule. Lecture seule [`ITable`](../itable). |
| [TextAnchorType](../../aspose.slides/icell/textanchortype) { get; set; } | Renvoie ou définit le type d'ancre du texte. Lecture/écriture [`TextAnchorType`](../textanchortype). |
| [TextFrame](../../aspose.slides/icell/textframe) { get; } | Renvoie le cadre de texte d'une cellule. Lecture seule [`ITextFrame`](../itextframe). |
| [TextVerticalType](../../aspose.slides/icell/textverticaltype) { get; set; } | Renvoie ou définit le type de texte vertical. Lecture/écriture [`TextVerticalType`](../textverticaltype). |
| [Width](../../aspose.slides/icell/width) { get; } | Renvoie la largeur de la cellule. Lecture seule Double. |

## Méthodes

| Name | Description |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/icell/splitbycolspan)(int) | Divise la cellule en deux cellules en fonction de l'index de la colonne. |
| [SplitByHeight](../../aspose.slides/icell/splitbyheight)(double) | Divise la cellule en fonction de la hauteur. |
| [SplitByRowSpan](../../aspose.slides/icell/splitbyrowspan)(int) | Divise la cellule en deux cellules en fonction de l'index de la ligne. |
| [SplitByWidth](../../aspose.slides/icell/splitbywidth)(double) | Divise la cellule en fonction de la largeur. |

### Voir aussi

* interface [ISlideComponent](../islidecomponent)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->