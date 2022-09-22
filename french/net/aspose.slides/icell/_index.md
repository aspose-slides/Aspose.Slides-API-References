---
title: ICell
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une cellule dans un tableau.
type: docs
weight: 4980
url: /fr/net/aspose.slides/icell/
---
## ICell interface

Représente une cellule dans un tableau.

```csharp
public interface ICell : ISlideComponent
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AnchorCenter](../../aspose.slides/icell/anchorcenter) { get; set; } | Détermine si la zone de texte est centrée ou non dans une cellule. Lecture/écritureBoolean . |
| [AsISlideComponent](../../aspose.slides/icell/asislidecomponent) { get; } | Permet d'obtenir l'interface ISlideComponent de base. Lecture seule[`ISlideComponent`](../islidecomponent) . |
| [CellFormat](../../aspose.slides/icell/cellformat) { get; } | Renvoie l'objet CellFormat qui contient les propriétés de mise en forme de cette cellule. Lecture seule[`ICellFormat`](../icellformat) . |
| [ColSpan](../../aspose.slides/icell/colspan) { get; } | Renvoie le nombre de colonnes de la grille de la table parent grid qui doivent être couvertes par la cellule actuelle. Cette propriété permet aux cellules d'avoir l'apparence d'être fusionnées, car elles s'étendent sur les limites verticales des autres cellules du tableau. En lecture seuleInt32 . |
| [FirstColumn](../../aspose.slides/icell/firstcolumn) { get; } | Obtient la première colonne de la cellule. Lecture seule[`IColumn`](../icolumn) . |
| [FirstColumnIndex](../../aspose.slides/icell/firstcolumnindex) { get; } | Renvoie un index de la première colonne, couvert par la cellule. Lecture seuleInt32 . |
| [FirstRow](../../aspose.slides/icell/firstrow) { get; } | Obtient la première ligne de la cellule. Lecture seule[`IRow`](../irow) . |
| [FirstRowIndex](../../aspose.slides/icell/firstrowindex) { get; } | Renvoie un index de la première ligne, couvert par la cellule. Lecture seuleInt32 . |
| [Height](../../aspose.slides/icell/height) { get; } | Renvoie la hauteur de la cellule. Lecture seuleDouble . |
| [IsMergedCell](../../aspose.slides/icell/ismergedcell) { get; } | Renvoie vrai si la cellule est fusionnée avec une cellule ajustée, faux sinon. Lecture seuleBoolean . |
| [MarginBottom](../../aspose.slides/icell/marginbottom) { get; set; } | Renvoie ou définit la marge inférieure dans un TextFrame. Lecture/écritureDouble . |
| [MarginLeft](../../aspose.slides/icell/marginleft) { get; set; } | Renvoie ou définit la marge gauche dans un TextFrame. Lecture/écritureDouble . |
| [MarginRight](../../aspose.slides/icell/marginright) { get; set; } | Renvoie ou définit la marge droite dans un TextFrame. Lecture/écritureDouble . |
| [MarginTop](../../aspose.slides/icell/margintop) { get; set; } | Renvoie ou définit la marge supérieure dans un TextFrame. Lecture/écritureDouble . |
| [MinimalHeight](../../aspose.slides/icell/minimalheight) { get; } | Renvoie la hauteur minimale d'une cellule. Il s'agit de la somme des hauteurs minimales de toutes les lignes recroquevillées par la cellule. Lecture seuleDouble . |
| [OffsetX](../../aspose.slides/icell/offsetx) { get; } | Renvoie une distance entre le côté gauche d'un tableau et le côté gauche d'une cellule. Lecture seuleDouble . |
| [OffsetY](../../aspose.slides/icell/offsety) { get; } | Renvoie une distance entre le côté supérieur d'un tableau et le côté supérieur d'une cellule. Lecture seuleDouble . |
| [RowSpan](../../aspose.slides/icell/rowspan) { get; } | Renvoie le nombre de lignes sur lesquelles s'étend une cellule fusionnée. Ceci est utilisé en combinaison avec l'attribut vMerge sur d'autres cellules afin de spécifier la cellule de début d'une fusion horizontale. Lecture seuleInt32 . |
| [Table](../../aspose.slides/icell/table) { get; } | Renvoie l'objet Table parent d'une cellule. Lecture seule[`ITable`](../itable) . |
| [TextAnchorType](../../aspose.slides/icell/textanchortype) { get; set; } | Renvoie ou définit le type d'ancre de texte. Lecture/écriture[`TextAnchorType`](../textanchortype) . |
| [TextFrame](../../aspose.slides/icell/textframe) { get; } | Renvoie le cadre de texte d'une cellule. Lecture seule[`ITextFrame`](../itextframe) . |
| [TextVerticalType](../../aspose.slides/icell/textverticaltype) { get; set; } | Renvoie ou définit le type de texte vertical. Lecture/écriture[`TextVerticalType`](../textverticaltype) . |
| [Width](../../aspose.slides/icell/width) { get; } | Renvoie la largeur de la cellule. Lecture seuleDouble . |

## Méthodes

| Nom | La description |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/icell/splitbycolspan)(int) | Divise la cellule en deux cellules par index de colonne. |
| [SplitByHeight](../../aspose.slides/icell/splitbyheight)(double) | Divise la cellule par hauteur. |
| [SplitByRowSpan](../../aspose.slides/icell/splitbyrowspan)(int) | Divise la cellule en deux cellules par index de ligne. |
| [SplitByWidth](../../aspose.slides/icell/splitbywidth)(double) | Divise la cellule par largeur. |

### Voir également

* interface [ISlideComponent](../islidecomponent)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
