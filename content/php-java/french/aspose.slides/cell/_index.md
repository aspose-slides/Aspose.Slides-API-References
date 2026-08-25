---
title: Cell
second_title: Référence de l'API Java Aspose.Sildes pour PHP
description: 
type: docs

url: /fr/aspose.slides/cell/
---
## Cell classe

Représente une cellule d'un tableau.

### getAnchorCenter {#getAnchorCenter}

| Nom | Description |
| --- | --- |
| getAnchorCenter () | Détermine si la zone de texte est centrée à l’intérieur d’une cellule. Lecture/écriture boolean. |

**Renvoie :**
boolean


---


### getCellFormat {#getCellFormat}

| Nom | Description |
| --- | --- |
| getCellFormat () | Renvoie l’objet CellFormat qui contient les propriétés de mise en forme pour cette cellule. Lecture seule ICellFormat. |

**Renvoie :**
[CellFormat](../cellformat)


---


### getColSpan {#getColSpan}

| Nom | Description |
| --- | --- |
| getColSpan () | Renvoie le nombre de colonnes de la grille du tableau parent qui doit être occupé par la cellule actuelle. Cette propriété permet aux cellules d’avoir l’apparence d’être fusionnées, puisqu’elles couvrent les limites verticales d’autres cellules du tableau. Lecture seule int. |

**Renvoie :**
int


---


### getFirstColumn {#getFirstColumn}

| Nom | Description |
| --- | --- |
| getFirstColumn () | Obtient la première colonne de la cellule. Lecture seule IColumn. |

**Renvoie :**
[Column](../column)


---


### getFirstColumnIndex {#getFirstColumnIndex}

| Nom | Description |
| --- | --- |
| getFirstColumnIndex () | Renvoie l’indice de la première colonne couverte par la cellule. Lecture seule int. |

**Renvoie :**
int


---


### getFirstRow {#getFirstRow}

| Nom | Description |
| --- | --- |
| getFirstRow () | Obtient la première ligne de la cellule. Lecture seule IRow. |

**Renvoie :**
[Row](../row)


---


### getFirstRowIndex {#getFirstRowIndex}

| Nom | Description |
| --- | --- |
| getFirstRowIndex () | Renvoie l’indice de la première ligne couverte par la cellule. Lecture seule int. |

**Renvoie :**
int


---


### getHeight {#getHeight}

| Nom | Description |
| --- | --- |
| getHeight () | Renvoie la hauteur de la cellule. Lecture seule double. |

**Renvoie :**
double


---


### getMarginBottom {#getMarginBottom}

| Nom | Description |
| --- | --- |
| getMarginBottom () | Renvoie ou définit la marge inférieure dans un TextFrame. Lecture/écriture double. |

**Renvoie :**
double


---


### getMarginLeft {#getMarginLeft}

| Nom | Description |
| --- | --- |
| getMarginLeft () | Renvoie ou définit la marge gauche dans un TextFrame. Lecture/écriture double. |

**Renvoie :**
double


---


### getMarginRight {#getMarginRight}

| Nom | Description |
| --- | --- |
| getMarginRight () | Renvoie ou définit la marge droite dans un TextFrame. Lecture/écriture double. |

**Renvoie :**
double


---


### getMarginTop {#getMarginTop}

| Nom | Description |
| --- | --- |
| getMarginTop () | Renvoie ou définit la marge supérieure dans un TextFrame. Lecture/écriture double. |

**Renvoie :**
double


---


### getMinimalHeight {#getMinimalHeight}

| Nom | Description |
| --- | --- |
| getMinimalHeight () | Renvoie la hauteur minimale d’une cellule. Il s’agit de la somme des hauteurs minimales de toutes les lignes couvertes par la cellule. Lecture seule double. |

**Renvoie :**
double


---


### getOffsetX {#getOffsetX}

| Nom | Description |
| --- | --- |
| getOffsetX () | Renvoie la distance du côté gauche d’un tableau au côté gauche de la cellule. Lecture seule double. |

**Renvoie :**
double


---


### getOffsetY {#getOffsetY}

| Nom | Description |
| --- | --- |
| getOffsetY () | Renvoie la distance du côté supérieur d’un tableau au côté supérieur de la cellule. Lecture seule double. |

**Renvoie :**
double


---


### getPresentation {#getPresentation}

| Nom | Description |
| --- | --- |
| getPresentation () | Renvoie la présentation parent d’une cellule. Lecture seule IPresentation. |

**Renvoie :**
[Presentation](../presentation)


---


### getRowSpan {#getRowSpan}

| Nom | Description |
| --- | --- |
| getRowSpan () | Renvoie le nombre de lignes qu’une cellule fusionnée occupe. Ceci est utilisé en combinaison avec l’attribut vMerge sur d’autres cellules afin de spécifier la cellule de départ d’une fusion horizontale. Lecture seule int. |

**Renvoie :**
int


---


### getSlide {#getSlide}

| Nom | Description |
| --- | --- |
| getSlide () | Renvoie la diapositive parent d’une cellule. Lecture seule IBaseSlide. |

**Renvoie :**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getTable {#getTable}

| Nom | Description |
| --- | --- |
| getTable () | Renvoie l’objet Table parent d’une cellule. Lecture seule ITable. |

**Renvoie :**
[Table](../table)


---


### getTextAnchorType {#getTextAnchorType}

| Nom | Description |
| --- | --- |
| getTextAnchorType () | Renvoie ou définit le type d’ancrage du texte. Lecture/écriture TextAnchorType. |

**Renvoie :**
byte


---


### getTextFrame {#getTextFrame}

| Nom | Description |
| --- | --- |
| getTextFrame () | Renvoie le cadre texte d’une cellule. Lecture seule ITextFrame. |

**Renvoie :**
[TextFrame](../textframe)


---


### getTextVerticalType {#getTextVerticalType}

| Nom | Description |
| --- | --- |
| getTextVerticalType () | Renvoie ou définit le type de texte vertical. Lecture/écriture TextVerticalType. |

**Renvoie :**
byte


---


### getWidth {#getWidth}

| Nom | Description |
| --- | --- |
| getWidth () | Renvoie la largeur de la cellule. Lecture seule double. |

**Renvoie :**
double


---


### isMergedCell {#isMergedCell}

| Nom | Description |
| --- | --- |
| isMergedCell () | Renvoie true si la cellule est fusionnée avec une cellule adjacente, false sinon. Lecture seule boolean. |

**Renvoie :**
boolean


---


### setAnchorCenter {#setAnchorCenter}

| Nom | Description |
| --- | --- |
| setAnchorCenter (boolean) | Détermine si la zone de texte est centrée à l’intérieur d’une cellule. Lecture/écriture boolean. |

**Renvoie :**
void


---


### setMarginBottom {#setMarginBottom}

| Nom | Description |
| --- | --- |
| setMarginBottom (double) | Renvoie ou définit la marge inférieure dans un TextFrame. Lecture/écriture double. |

**Renvoie :**
void


---


### setMarginLeft {#setMarginLeft}

| Nom | Description |
| --- | --- |
| setMarginLeft (double) | Renvoie ou définit la marge gauche dans un TextFrame. Lecture/écriture double. |

**Renvoie :**
void


---


### setMarginRight {#setMarginRight}

| Nom | Description |
| --- | --- |
| setMarginRight (double) | Renvoie ou définit la marge droite dans un TextFrame. Lecture/écriture double. |

**Renvoie :**
void


---


### setMarginTop {#setMarginTop}

| Nom | Description |
| --- | --- |
| setMarginTop (double) | Renvoie ou définit la marge supérieure dans un TextFrame. Lecture/écriture double. |

**Renvoie :**
void


---


### setTextAnchorType {#setTextAnchorType}

| Nom | Description |
| --- | --- |
| setTextAnchorType (byte) | Renvoie ou définit le type d’ancrage du texte. Lecture/écriture TextAnchorType. |

**Renvoie :**
void


---


### setTextVerticalType {#setTextVerticalType}

| Nom | Description |
| --- | --- |
| setTextVerticalType (byte) | Renvoie ou définit le type de texte vertical. Lecture/écriture TextVerticalType. |

**Renvoie :**
void


---


### splitByColSpan {#splitByColSpan}

| Nom | Description |
| --- | --- |
| splitByColSpan (int) | Divise la cellule en deux cellules selon l’indice de la colonne. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Indice de la colonne. |

**Renvoie :**
void


---


### splitByHeight {#splitByHeight}

| Nom | Description |
| --- | --- |
| splitByHeight (double) | Divise la cellule selon la hauteur. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| height | double | Hauteur d’une ligne. |

**Renvoie :**
void


---


### splitByRowSpan {#splitByRowSpan}

| Nom | Description |
| --- | --- |
| splitByRowSpan (int) | Divise la cellule en deux cellules selon l’indice de la ligne. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | Indice de la ligne. |

**Renvoie :**
void


---


### splitByWidth {#splitByWidth}

| Nom | Description |
| --- | --- |
| splitByWidth (double) | Divise la cellule selon la largeur. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| width | double | Largeur d’une colonne. |

**Renvoie :**
void


---  