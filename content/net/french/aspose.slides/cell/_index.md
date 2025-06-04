---
title: Cell
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une cellule d'un tableau.
type: docs
weight: 1050
url: /fr/aspose.slides/cell/
---

## Classe Cell

Représente une cellule d'un tableau.

```csharp
public class Cell : ICell
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AnchorCenter](../../aspose.slides/cell/anchorcenter) { get; set; } | Détermine si la zone de texte est centrée à l'intérieur d'une cellule. Booléen en lecture/écriture. |
| [CellFormat](../../aspose.slides/cell/cellformat) { get; } | Renvoie l'objet CellFormat qui contient les propriétés de mise en forme pour cette cellule. Lecture seule [`ICellFormat`](../icellformat). |
| [ColSpan](../../aspose.slides/cell/colspan) { get; } | Renvoie le nombre de colonnes de la grille du tableau parent que la cellule actuelle doit occuper. Cette propriété permet aux cellules d'avoir l'apparence d'être fusionnées, car elles traversent les frontières verticales d'autres cellules du tableau. Lecture seule Int32. |
| [FirstColumn](../../aspose.slides/cell/firstcolumn) { get; } | Obtient la première colonne de la cellule. Lecture seule [`IColumn`](../icolumn). |
| [FirstColumnIndex](../../aspose.slides/cell/firstcolumnindex) { get; } | Renvoie un index de la première colonne, couverte par la cellule. Lecture seule Int32. |
| [FirstRow](../../aspose.slides/cell/firstrow) { get; } | Obtient la première ligne de la cellule. Lecture seule [`IRow`](../irow). |
| [FirstRowIndex](../../aspose.slides/cell/firstrowindex) { get; } | Renvoie un index de la première ligne, couverte par la cellule. Lecture seule Int32. |
| [Height](../../aspose.slides/cell/height) { get; } | Renvoie la hauteur de la cellule. Lecture seule Double. |
| [IsMergedCell](../../aspose.slides/cell/ismergedcell) { get; } | Renvoie true si la cellule est fusionnée avec une cellule ajustée, false sinon. Lecture seule Booléen. |
| [MarginBottom](../../aspose.slides/cell/marginbottom) { get; set; } | Renvoie ou définit la marge inférieure dans un TextFrame. Lecture/écriture Double. |
| [MarginLeft](../../aspose.slides/cell/marginleft) { get; set; } | Renvoie ou définit la marge gauche dans un TextFrame. Lecture/écriture Double. |
| [MarginRight](../../aspose.slides/cell/marginright) { get; set; } | Renvoie ou définit la marge droite dans un TextFrame. Lecture/écriture Double. |
| [MarginTop](../../aspose.slides/cell/margintop) { get; set; } | Renvoie ou définit la marge supérieure dans un TextFrame. Lecture/écriture Double. |
| [MinimalHeight](../../aspose.slides/cell/minimalheight) { get; } | Renvoie la hauteur minimale d'une cellule. Il s'agit d'une somme des hauteurs minimales de toutes les lignes couvertes par la cellule. Lecture seule Double. |
| [OffsetX](../../aspose.slides/cell/offsetx) { get; } | Renvoie une distance du côté gauche d'un tableau au côté gauche d'une cellule. Lecture seule Double. |
| [OffsetY](../../aspose.slides/cell/offsety) { get; } | Renvoie une distance du côté supérieur d'un tableau au côté supérieur d'une cellule. Lecture seule Double. |
| [Presentation](../../aspose.slides/cell/presentation) { get; } | Renvoie la présentation parente d'une cellule. Lecture seule [`IPresentation`](../ipresentation). |
| [RowSpan](../../aspose.slides/cell/rowspan) { get; } | Renvoie le nombre de lignes que couvre une cellule fusionnée. Cela est utilisé en combinaison avec l'attribut vMerge sur d'autres cellules afin de spécifier la cellule de début d'une fusion horizontale. Lecture seule Int32. |
| [Slide](../../aspose.slides/cell/slide) { get; } | Renvoie la diapositive parente d'une cellule. Lecture seule [`IBaseSlide`](../ibaseslide). |
| [Table](../../aspose.slides/cell/table) { get; } | Renvoie l'objet Table parent pour une cellule. Lecture seule [`ITable`](../itable). |
| [TextAnchorType](../../aspose.slides/cell/textanchortype) { get; set; } | Renvoie ou définit le type d'ancrage du texte. Lecture/écriture [`TextAnchorType`](../textanchortype). |
| [TextFrame](../../aspose.slides/cell/textframe) { get; } | Renvoie le cadre de texte d'une cellule. Lecture seule [`ITextFrame`](../itextframe). |
| [TextVerticalType](../../aspose.slides/cell/textverticaltype) { get; set; } | Renvoie ou définit le type de texte vertical. Lecture/écriture [`TextVerticalType`](../textverticaltype). |
| [Width](../../aspose.slides/cell/width) { get; } | Renvoie la largeur de la cellule. Lecture seule Double. |

## Méthodes

| Nom | Description |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/cell/splitbycolspan)(int) | Divise la cellule en deux cellules par l'index de colonne. |
| [SplitByHeight](../../aspose.slides/cell/splitbyheight)(double) | Divise la cellule par hauteur. |
| [SplitByRowSpan](../../aspose.slides/cell/splitbyrowspan)(int) | Divise la cellule en deux cellules par l'index de ligne. |
| [SplitByWidth](../../aspose.slides/cell/splitbywidth)(double) | Divise la cellule par largeur. |

### Voir Aussi

* interface [ICell](../icell)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->