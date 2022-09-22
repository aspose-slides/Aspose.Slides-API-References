---
title: Cell
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une cellule dun tableau.
type: docs
weight: 1010
url: /fr/net/aspose.slides/cell/
---
## Cell class

Représente une cellule d'un tableau.

```csharp
public class Cell : ICell
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AnchorCenter](../../aspose.slides/cell/anchorcenter) { get; set; } | Détermine si la zone de texte est centrée ou non dans une cellule. Lecture/écritureBoolean . |
| [CellFormat](../../aspose.slides/cell/cellformat) { get; } | Renvoie l'objet CellFormat qui contient les propriétés de mise en forme de cette cellule. Lecture seule[`ICellFormat`](../icellformat) . |
| [ColSpan](../../aspose.slides/cell/colspan) { get; } | Renvoie le nombre de colonnes de la grille de la table parent grid qui doivent être couvertes par la cellule actuelle. Cette propriété permet aux cellules d'avoir l'apparence d'être fusionnées, car elles s'étendent sur les limites verticales des autres cellules du tableau. En lecture seuleInt32 . |
| [FirstColumn](../../aspose.slides/cell/firstcolumn) { get; } | Obtient la première colonne de la cellule. Lecture seule[`IColumn`](../icolumn) . |
| [FirstColumnIndex](../../aspose.slides/cell/firstcolumnindex) { get; } | Renvoie un index de la première colonne, couvert par la cellule. Lecture seuleInt32 . |
| [FirstRow](../../aspose.slides/cell/firstrow) { get; } | Obtient la première ligne de la cellule. Lecture seule[`IRow`](../irow) . |
| [FirstRowIndex](../../aspose.slides/cell/firstrowindex) { get; } | Renvoie un index de la première ligne, couvert par la cellule. Lecture seuleInt32 . |
| [Height](../../aspose.slides/cell/height) { get; } | Renvoie la hauteur de la cellule. Lecture seuleDouble . |
| [IsMergedCell](../../aspose.slides/cell/ismergedcell) { get; } | Renvoie vrai si la cellule est fusionnée avec une cellule ajustée, faux sinon. Lecture seuleBoolean . |
| [MarginBottom](../../aspose.slides/cell/marginbottom) { get; set; } | Renvoie ou définit la marge inférieure dans un TextFrame. Lecture/écritureDouble . |
| [MarginLeft](../../aspose.slides/cell/marginleft) { get; set; } | Renvoie ou définit la marge gauche dans un TextFrame. Lecture/écritureDouble . |
| [MarginRight](../../aspose.slides/cell/marginright) { get; set; } | Renvoie ou définit la marge droite dans un TextFrame. Lecture/écritureDouble . |
| [MarginTop](../../aspose.slides/cell/margintop) { get; set; } | Renvoie ou définit la marge supérieure dans un TextFrame. Lecture/écritureDouble . |
| [MinimalHeight](../../aspose.slides/cell/minimalheight) { get; } | Renvoie la hauteur minimale d'une cellule. Il s'agit de la somme des hauteurs minimales de toutes les lignes recroquevillées par la cellule. Lecture seuleDouble . |
| [OffsetX](../../aspose.slides/cell/offsetx) { get; } | Renvoie une distance entre le côté gauche d'un tableau et le côté gauche d'une cellule. Lecture seuleDouble . |
| [OffsetY](../../aspose.slides/cell/offsety) { get; } | Renvoie une distance entre le côté supérieur d'un tableau et le côté supérieur d'une cellule. Lecture seuleDouble . |
| [Presentation](../../aspose.slides/cell/presentation) { get; } | Renvoie la présentation parent d'une cellule. Lecture seule[`IPresentation`](../ipresentation) . |
| [RowSpan](../../aspose.slides/cell/rowspan) { get; } | Renvoie le nombre de lignes sur lesquelles s'étend une cellule fusionnée. Ceci est utilisé en combinaison avec l'attribut vMerge sur d'autres cellules afin de spécifier la cellule de début d'une fusion horizontale. Lecture seuleInt32 . |
| [Slide](../../aspose.slides/cell/slide) { get; } | Renvoie la diapositive parent d'une cellule. Lecture seule[`IBaseSlide`](../ibaseslide) . |
| [Table](../../aspose.slides/cell/table) { get; } | Renvoie l'objet Table parent d'une cellule. Lecture seule[`ITable`](../itable) . |
| [TextAnchorType](../../aspose.slides/cell/textanchortype) { get; set; } | Renvoie ou définit le type d'ancre de texte. Lecture/écriture[`TextAnchorType`](../textanchortype) . |
| [TextFrame](../../aspose.slides/cell/textframe) { get; } | Renvoie le cadre de texte d'une cellule. Lecture seule[`ITextFrame`](../itextframe) . |
| [TextVerticalType](../../aspose.slides/cell/textverticaltype) { get; set; } | Renvoie ou définit le type de texte vertical. Lecture/écriture[`TextVerticalType`](../textverticaltype) . |
| [Width](../../aspose.slides/cell/width) { get; } | Renvoie la largeur de la cellule. Lecture seuleDouble . |

## Méthodes

| Nom | La description |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/cell/splitbycolspan)(int) | Divise la cellule en deux cellules par index de colonne. |
| [SplitByHeight](../../aspose.slides/cell/splitbyheight)(double) | Divise la cellule par hauteur. |
| [SplitByRowSpan](../../aspose.slides/cell/splitbyrowspan)(int) | Divise la cellule en deux cellules par index de ligne. |
| [SplitByWidth](../../aspose.slides/cell/splitbywidth)(double) | Divise la cellule par largeur. |

### Voir également

* interface [ICell](../icell)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
