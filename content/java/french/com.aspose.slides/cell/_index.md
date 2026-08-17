---
title: Cell
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une cellule d'un tableau.
type: docs
url: /fr/com.aspose.slides/cell/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

Représente une cellule d’un tableau.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Renvoie la distance du côté gauche du tableau au côté gauche de la cellule. |
| [getOffsetY()](#getOffsetY--) | Renvoie la distance du côté supérieur du tableau au côté supérieur de la cellule. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Renvoie l’index de la première ligne couverte par la cellule. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Renvoie l’index de la première colonne couverte par la cellule. |
| [getWidth()](#getWidth--) | Renvoie la largeur de la cellule. |
| [getHeight()](#getHeight--) | Renvoie la hauteur de la cellule. |
| [getMinimalHeight()](#getMinimalHeight--) | Renvoie la hauteur minimale d’une cellule. |
| [getMarginLeft()](#getMarginLeft--) | Renvoie ou définit la marge gauche dans un TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Renvoie ou définit la marge gauche dans un TextFrame. |
| [getMarginRight()](#getMarginRight--) | Renvoie ou définit la marge droite dans un TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Renvoie ou définit la marge droite dans un TextFrame. |
| [getMarginTop()](#getMarginTop--) | Renvoie ou définit la marge supérieure dans un TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Renvoie ou définit la marge supérieure dans un TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Renvoie ou définit la marge inférieure dans un TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Renvoie ou définit la marge inférieure dans un TextFrame. |
| [getTextVerticalType()](#getTextVerticalType--) | Renvoie ou définit le type de texte vertical. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Renvoie ou définit le type de texte vertical. |
| [getTextAnchorType()](#getTextAnchorType--) | Renvoie ou définit le type d’ancrage du texte. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Renvoie ou définit le type d’ancrage du texte. |
| [getAnchorCenter()](#getAnchorCenter--) | Détermine si la zone de texte est centrée à l’intérieur de la cellule. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Détermine si la zone de texte est centrée à l’intérieur de la cellule. |
| [getFirstRow()](#getFirstRow--) | Obtient la première ligne de la cellule. |
| [getFirstColumn()](#getFirstColumn--) | Obtient la première colonne de la cellule. |
| [getColSpan()](#getColSpan--) | Renvoie le nombre de colonnes de la grille du tableau parent qui doivent être englobées par la cellule actuelle. |
| [getRowSpan()](#getRowSpan--) | Renvoie le nombre de lignes qu’une cellule fusionnée occupe. |
| [getTextFrame()](#getTextFrame--) | Renvoie le cadre texte d’une cellule. |
| [getTable()](#getTable--) | Renvoie l’objet Table parent d’une cellule. |
| [isMergedCell()](#isMergedCell--) | Renvoie true si la cellule est fusionnée avec une autre cellule ajustée, false sinon. |
| [getCellFormat()](#getCellFormat--) | Renvoie l’objet CellFormat contenant les propriétés de formatage de cette cellule. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Divise la cellule en deux cellules selon l’indice de colonne. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Divise la cellule en deux cellules selon l’indice de ligne. |
| [splitByHeight(double height)](#splitByHeight-double-) | Divise la cellule selon la hauteur. |
| [splitByWidth(double width)](#splitByWidth-double-) | Divise la cellule selon la largeur. |
| [getSlide()](#getSlide--) | Renvoie la diapositive parent d’une cellule. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation parent d’une cellule. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

Renvoie une distance du côté gauche du tableau au côté gauche de la cellule. Lecture seule double.

**Renvoie :**
double
### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

Renvoie une distance du côté supérieur du tableau au côté supérieur de la cellule. Lecture seule double.

**Renvoie :**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

Renvoie l’index de la première ligne couverte par la cellule. Lecture seule int.

**Renvoie :**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

Renvoie l’index de la première colonne couverte par la cellule. Lecture seule int.

**Renvoie :**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Renvoie la largeur de la cellule. Lecture seule double.

**Renvoie :**
double
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Renvoie la hauteur de la cellule. Lecture seule double.

**Renvoie :**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Renvoie la hauteur minimale d’une cellule. Il s’agit de la somme des hauteurs minimales de toutes les lignes couvertes par la cellule. Lecture seule double.

**Renvoie :**
double
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Renvoie ou définit la marge gauche dans un TextFrame. Lecture/écriture double.

**Renvoie :**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Renvoie ou définit la marge gauche dans un TextFrame. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Renvoie ou définit la marge droite dans un TextFrame. Lecture/écriture double.

**Renvoie :**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Renvoie ou définit la marge droite dans un TextFrame. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Renvoie ou définit la marge supérieure dans un TextFrame. Lecture/écriture double.

**Renvoie :**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Renvoie ou définit la marge supérieure dans un TextFrame. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Renvoie ou définit la marge inférieure dans un TextFrame. Lecture/écriture double.

**Renvoie :**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Renvoie ou définit la marge inférieure dans un TextFrame. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Renvoie ou définit le type de texte vertical. Lecture/écriture [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Renvoie :**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Renvoie ou définit le type de texte vertical. Lecture/écriture [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

Renvoie ou définit le type d’ancrage du texte. Lecture/écriture [TextAnchorType](../../com.aspose.slides/textanchortype).

**Renvoie :**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

Renvoie ou définit le type d’ancrage du texte. Lecture/écriture [TextAnchorType](../../com.aspose.slides/textanchortype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

Détermine si la zone de texte est centrée à l’intérieur de la cellule. Lecture/écriture boolean.

**Renvoie :**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

Détermine si la zone de texte est centrée à l’intérieur de la cellule. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

Obtient la première ligne de la cellule. Lecture seule [IRow](../../com.aspose.slides/irow).

**Renvoie :**
[IRow](../../com.aspose.slides/irow)
### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

Obtient la première colonne de la cellule. Lecture seule [IColumn](../../com.aspose.slides/icolumn).

**Renvoie :**
[IColumn](../../com.aspose.slides/icolumn)
### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

Renvoie le nombre de colonnes de la grille du tableau parent qui doivent être englobées par la cellule actuelle. Cette propriété permet aux cellules d’apparaître comme fusionnées, car elles s’étendent sur les limites verticales d’autres cellules du tableau. Lecture seule int.

**Renvoie :**
int
### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

Renvoie le nombre de lignes qu’une cellule fusionnée occupe. Cette valeur est utilisée en combinaison avec l’attribut vMerge sur d’autres cellules afin de spécifier la cellule de départ d’une fusion horizontale. Lecture seule int.

**Renvoie :**
int
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Renvoie le cadre texte d’une cellule. Lecture seule [ITextFrame](../../com.aspose.slides/itextframe).

**Renvoie :**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public final ITable getTable()
```

Renvoie l’objet Table parent d’une cellule. Lecture seule [ITable](../../com.aspose.slides/itable).

**Renvoie :**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

Renvoie true si la cellule est fusionnée avec une autre cellule ajustée, false sinon. Lecture seule boolean.

**Renvoie :**
boolean
### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

Renvoie l’objet CellFormat contenant les propriétés de formatage de cette cellule. Lecture seule [ICellFormat](../../com.aspose.slides/icellformat).

**Renvoie :**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

Divise la cellule en deux cellules selon l’indice de colonne.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice de la colonne. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

Divise la cellule en deux cellules selon l’indice de ligne.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice de la ligne. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

Divise la cellule selon la hauteur.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| height | double | Hauteur d’une ligne. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

Divise la cellule selon la largeur.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | double | Largeur d’une colonne. |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Renvoie la diapositive parent d’une cellule. Lecture seule [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Renvoie :**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Renvoie la présentation parent d’une cellule. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie :**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l’objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject