---
title: Cell
second_title: Référence API Aspose.Slides pour .NET
description: Représente une cellule d'un tableau.
type: docs
weight: 1050
url: /fr/aspose.slides/cell/
---

## Classe Cellule

Représente une cellule d'un tableau.

```csharp
public class Cell : ICell
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AnchorCenter](../../aspose.slides/cell/anchorcenter) { get; set; } | Détermine si la zone de texte est centrée à l'intérieur d'une cellule. Booléen en lecture/écriture. |
| [CellFormat](../../aspose.slides/cell/cellformat) { get; } | Renvoie l'objet CellFormat qui contient les propriétés de formatage pour cette cellule. En lecture seule [`ICellFormat`](../icellformat). |
| [ColSpan](../../aspose.slides/cell/colspan) { get; } | Renvoie le nombre de colonnes de la grille dans la grille de tableau de la table parente qui seront recouvertes par la cellule actuelle. Cette propriété permet aux cellules d'avoir l'apparence d'être fusionnées, car elles dépassent les limites verticales des autres cellules du tableau. En lecture seule Int32. |
| [FirstColumn](../../aspose.slides/cell/firstcolumn) { get; } | Obtient la première colonne de la cellule. En lecture seule [`IColumn`](../icolumn). |
| [FirstColumnIndex](../../aspose.slides/cell/firstcolumnindex) { get; } | Renvoie un index de la première colonne, couverte par la cellule. En lecture seule Int32. |
| [FirstRow](../../aspose.slides/cell/firstrow) { get; } | Obtient la première ligne de la cellule. En lecture seule [`IRow`](../irow). |
| [FirstRowIndex](../../aspose.slides/cell/firstrowindex) { get; } | Renvoie un index de la première ligne, couverte par la cellule. En lecture seule Int32. |
| [Height](../../aspose.slides/cell/height) { get; } | Renvoie la hauteur de la cellule. En lecture seule Double. |
| [IsMergedCell](../../aspose.slides/cell/ismergedcell) { get; } | Renvoie true si la cellule est fusionnée avec une cellule ajustée, false sinon. En lecture seule Booléen. |
| [MarginBottom](../../aspose.slides/cell/marginbottom) { get; set; } | Renvoie ou définit la marge inférieure dans un TextFrame. En lecture/écriture Double. |
| [MarginLeft](../../aspose.slides/cell/marginleft) { get; set; } | Renvoie ou définit la marge gauche dans un TextFrame. En lecture/écriture Double. |
| [MarginRight](../../aspose.slides/cell/marginright) { get; set; } | Renvoie ou définit la marge droite dans un TextFrame. En lecture/écriture Double. |
| [MarginTop](../../aspose.slides/cell/margintop) { get; set; } | Renvoie ou définit la marge supérieure dans un TextFrame. En lecture/écriture Double. |
| [MinimalHeight](../../aspose.slides/cell/minimalheight) { get; } | Renvoie la hauteur minimale d'une cellule. C'est la somme des hauteurs minimales de toutes les lignes couvertes par la cellule. En lecture seule Double. |
| [OffsetX](../../aspose.slides/cell/offsetx) { get; } | Renvoie une distance du côté gauche d'un tableau au côté gauche d'une cellule. En lecture seule Double. |
| [OffsetY](../../aspose.slides/cell/offsety) { get; } | Renvoie une distance du côté supérieur d'un tableau au côté supérieur d'une cellule. En lecture seule Double. |
| [Presentation](../../aspose.slides/cell/presentation) { get; } | Renvoie la présentation parente d'une cellule. En lecture seule [`IPresentation`](../ipresentation). |
| [RowSpan](../../aspose.slides/cell/rowspan) { get; } | Renvoie le nombre de lignes qu'une cellule fusionnée couvre. Cela est utilisé en combinaison avec l'attribut vMerge sur d'autres cellules afin de spécifier la cellule de début d'une fusion horizontale. En lecture seule Int32. |
| [Slide](../../aspose.slides/cell/slide) { get; } | Renvoie la diapositive parente d'une cellule. En lecture seule [`IBaseSlide`](../ibaseslide). |
| [Table](../../aspose.slides/cell/table) { get; } | Renvoie l'objet Table parente pour une cellule. En lecture seule [`ITable`](../itable). |
| [TextAnchorType](../../aspose.slides/cell/textanchortype) { get; set; } | Renvoie ou définit le type d'ancrage du texte. En lecture/écriture [`TextAnchorType`](../textanchortype). |
| [TextFrame](../../aspose.slides/cell/textframe) { get; } | Renvoie le cadre de texte d'une cellule. En lecture seule [`ITextFrame`](../itextframe). |
| [TextVerticalType](../../aspose.slides/cell/textverticaltype) { get; set; } | Renvoie ou définit le type de texte vertical. En lecture/écriture [`TextVerticalType`](../textverticaltype). |
| [Width](../../aspose.slides/cell/width) { get; } | Renvoie la largeur de la cellule. En lecture seule Double. |

## Méthodes

| Nom | Description |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/cell/splitbycolspan)(int) | Divise la cellule en deux cellules par l'index de colonne. |
| [SplitByHeight](../../aspose.slides/cell/splitbyheight)(double) | Divise la cellule par la hauteur. |
| [SplitByRowSpan](../../aspose.slides/cell/splitbyrowspan)(int) | Divise la cellule en deux cellules par l'index de ligne. |
| [SplitByWidth](../../aspose.slides/cell/splitbywidth)(double) | Divise la cellule par la largeur. |

### Voir également

* interface [ICell](../icell)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->