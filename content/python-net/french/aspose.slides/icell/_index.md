---
title: ICell class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/icell/
---
## ICell classe

Représente une cellule dans une table.

Le type ICell expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`offset_x`](/slides/python-net/fr/aspose.slides/icell/offset_x/) | Renvoie une distance entre le côté gauche d'une table et le côté gauche d'une cellule.<br/>            Lecture seule **float**. |
| [`offset_y`](/slides/python-net/fr/aspose.slides/icell/offset_y/) | Renvoie une distance entre le côté supérieur d'une table et le côté supérieur d'une cellule.<br/>            Lecture seule **float**. |
| [`first_row_index`](/slides/python-net/fr/aspose.slides/icell/first_row_index/) | Renvoie l'index de la première ligne couverte par la cellule.<br/>            Lecture seule **int**. |
| [`first_column_index`](/slides/python-net/fr/aspose.slides/icell/first_column_index/) | Renvoie l'index de la première colonne couverte par la cellule.<br/>            Lecture seule **int**. |
| [`width`](/slides/python-net/fr/aspose.slides/icell/width/) | Renvoie la largeur de la cellule.<br/>            Lecture seule **float**. |
| [`height`](/slides/python-net/fr/aspose.slides/icell/height/) | Renvoie la hauteur de la cellule.<br/>            Lecture seule **float**. |
| [`minimal_height`](/slides/python-net/fr/aspose.slides/icell/minimal_height/) | Renvoie la hauteur minimale d'une cellule.<br/>            Il s'agit de la somme des hauteurs minimales de toutes les lignes couvertes par la cellule.<br/>            Lecture seule **float**. |
| [`margin_left`](/slides/python-net/fr/aspose.slides/icell/margin_left/) | Renvoie ou définit la marge gauche dans un TextFrame.<br/>            Lecture/écriture **float**. |
| [`margin_right`](/slides/python-net/fr/aspose.slides/icell/margin_right/) | Renvoie ou définit la marge droite dans un TextFrame.<br/>            Lecture/écriture **float**. |
| [`margin_top`](/slides/python-net/fr/aspose.slides/icell/margin_top/) | Renvoie ou définit la marge supérieure dans un TextFrame.<br/>            Lecture/écriture **float**. |
| [`margin_bottom`](/slides/python-net/fr/aspose.slides/icell/margin_bottom/) | Renvoie ou définit la marge inférieure dans un TextFrame.<br/>            Lecture/écriture **float**. |
| [`text_vertical_type`](/slides/python-net/fr/aspose.slides/icell/text_vertical_type/) | Renvoie ou définit le type de texte vertical.<br/>            Lecture/écriture [`TextVerticalType`](/slides/python-net/fr/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/fr/aspose.slides/icell/text_anchor_type/) | Renvoie ou définit le type d'ancrage du texte.<br/>            Lecture/écriture [`TextAnchorType`](/slides/python-net/fr/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/fr/aspose.slides/icell/anchor_center/) | Détermine si la zone de texte est centrée à l'intérieur d'une cellule.<br/>            Lecture/écriture **bool**. |
| [`first_column`](/slides/python-net/fr/aspose.slides/icell/first_column/) | Obtient la première colonne de la cellule.<br/>            Lecture seule [`IColumn`](/slides/python-net/fr/aspose.slides/icolumn). |
| [`first_row`](/slides/python-net/fr/aspose.slides/icell/first_row/) | Obtient la première ligne de la cellule.<br/>            Lecture seule [`IRow`](/slides/python-net/fr/aspose.slides/irow). |
| [`col_span`](/slides/python-net/fr/aspose.slides/icell/col_span/) | Renvoie le nombre de colonnes de la grille du tableau parent<br/>            qui seront couvertes par la cellule actuelle. Cette propriété permet aux cellules<br/>            d'avoir l'apparence d'être fusionnées, car elles s'étendent sur les limites verticales<br/>            d'autres cellules du tableau.<br/>            Lecture seule **int**. |
| [`row_span`](/slides/python-net/fr/aspose.slides/icell/row_span/) | Renvoie le nombre de lignes qu'une cellule fusionnée couvre. Ceci est utilisé en combinaison<br/>            avec l'attribut vMerge sur d'autres cellules afin de spécifier la cellule de départ<br/>            d'une fusion horizontale.<br/>            Lecture seule **int**. |
| [`text_frame`](/slides/python-net/fr/aspose.slides/icell/text_frame/) | Renvoie le cadre texte d'une cellule.<br/>            Lecture seule [`ITextFrame`](/slides/python-net/fr/aspose.slides/itextframe). |
| [`table`](/slides/python-net/fr/aspose.slides/icell/table/) | Renvoie l'objet Table parent d'une cellule.<br/>            Lecture seule [`ITable`](/slides/python-net/fr/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/fr/aspose.slides/icell/is_merged_cell/) | Renvoie vrai si la cellule est fusionnée avec une cellule ajustée, sinon faux.<br/>            Lecture seule **bool**. |
| [`cell_format`](/slides/python-net/fr/aspose.slides/icell/cell_format/) | Renvoie l'objet CellFormat contenant les propriétés de mise en forme de cette cellule.<br/>            Lecture seule [`ICellFormat`](/slides/python-net/fr/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/fr/aspose.slides/icell/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides/icell/presentation/) |  |

## Méthodes

| Method | Description |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/fr/aspose.slides/icell/split_by_col_span/#int) | Divise la cellule en deux cellules selon l'index de la colonne. |
| [`split_by_row_span(self, index)`](/slides/python-net/fr/aspose.slides/icell/split_by_row_span/#int) | Divise la cellule en deux cellules selon l'index de la ligne. |
| [`split_by_height(self, height)`](/slides/python-net/fr/aspose.slides/icell/split_by_height/#float) | Divise la cellule selon la hauteur. |
| [`split_by_width(self, width)`](/slides/python-net/fr/aspose.slides/icell/split_by_width/#float) | Divise la cellule selon la largeur. |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)