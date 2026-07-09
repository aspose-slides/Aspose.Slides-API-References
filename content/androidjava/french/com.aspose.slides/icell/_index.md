---
title: ICell
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente une cellule dans un tableau.
type: docs
url: /fr/com.aspose.slides/icell/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

Représente une cellule dans un tableau.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Renvoie une distance du côté gauche d'un tableau au côté gauche d'une cellule. |
| [getOffsetY()](#getOffsetY--) | Renvoie une distance du côté supérieur d'un tableau au côté supérieur d'une cellule. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Renvoie l'indice de la première ligne couverte par la cellule. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Renvoie l'indice de la première colonne couverte par la cellule. |
| [getWidth()](#getWidth--) | Renvoie la largeur de la cellule. |
| [getHeight()](#getHeight--) | Renvoie la hauteur de la cellule. |
| [getMinimalHeight()](#getMinimalHeight--) | Renvoie la hauteur minimale d'une cellule. |
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
| [getTextAnchorType()](#getTextAnchorType--) | Renvoie ou définit le type d'ancrage du texte. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Renvoie ou définit le type d'ancrage du texte. |
| [getAnchorCenter()](#getAnchorCenter--) | Détermine si la zone de texte est centrée à l'intérieur d'une cellule. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Détermine si la zone de texte est centrée à l'intérieur d'une cellule. |
| [getFirstColumn()](#getFirstColumn--) | Obtient la première colonne de la cellule. |
| [getFirstRow()](#getFirstRow--) | Obtient la première ligne de la cellule. |
| [getColSpan()](#getColSpan--) | Renvoie le nombre de colonnes de la grille du tableau parent qui doivent être englobées par la cellule actuelle. |
| [getRowSpan()](#getRowSpan--) | Renvoie le nombre de lignes qu'une cellule fusionnée occupe. |
| [getTextFrame()](#getTextFrame--) | Renvoie le cadre de texte d'une cellule. |
| [getTable()](#getTable--) | Renvoie l'objet Table parent d'une cellule. |
| [isMergedCell()](#isMergedCell--) | Renvoie vrai si la cellule est fusionnée avec une cellule adjacente, faux sinon. |
| [getCellFormat()](#getCellFormat--) | Renvoie l'objet CellFormat qui contient les propriétés de formatage pour cette cellule. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Divise la cellule en deux cellules par indice de colonne. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Divise la cellule en deux cellules par indice de ligne. |
| [splitByHeight(double height)](#splitByHeight-double-) | Divise la cellule par hauteur. |
| [splitByWidth(double width)](#splitByWidth-double-) | Divise la cellule par largeur. |

### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```

Renvoie une distance du côté gauche d'un tableau au côté gauche d'une cellule. Lecture seule double.

**Renvoie :**
double

### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```

Renvoie une distance du côté supérieur d'un tableau au côté supérieur d'une cellule. Lecture seule double.

**Renvoie :**
double

### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```

Renvoie l'indice de la première ligne couverte par la cellule. Lecture seule int.

**Renvoie :**
int

### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```

Renvoie l'indice de la première colonne couverte par la cellule. Lecture seule int.

**Renvoie :**
int

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Renvoie la largeur de la cellule. Lecture seule double.

**Renvoie :**
double

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

Renvoie la hauteur de la cellule. Lecture seule double.

**Renvoie :**
double

### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

Renvoie la hauteur minimale d'une cellule. Il s'agit de la somme des hauteurs minimales de toutes les lignes couvertes par la cellule. Lecture seule double.

**Renvoie :**
double

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Renvoie ou définit la marge gauche dans un TextFrame. Lecture/écriture double.

**Renvoie :**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Renvoie ou définit la marge gauche dans un TextFrame. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Renvoie ou définit la marge droite dans un TextFrame. Lecture/écriture double.

**Renvoie :**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Renvoie ou définit la marge droite dans un TextFrame. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Renvoie ou définit la marge supérieure dans un TextFrame. Lecture/écriture double.

**Renvoie :**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Renvoie ou définit la marge supérieure dans un TextFrame. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Renvoie ou définit la marge inférieure dans un TextFrame. Lecture/écriture double.

**Renvoie :**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Renvoie ou définit la marge inférieure dans un TextFrame. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Renvoie ou définit le type de texte vertical. Lecture/écriture [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Renvoie :**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Renvoie ou définit le type de texte vertical. Lecture/écriture [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```

Renvoie ou définit le type d'ancrage du texte. Lecture/écriture [TextAnchorType](../../com.aspose.slides/textanchortype).

**Renvoie :**
byte

### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```

Renvoie ou définit le type d'ancrage du texte. Lecture/écriture [TextAnchorType](../../com.aspose.slides/textanchortype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```

Détermine si la zone de texte est centrée à l'intérieur d'une cellule. Lecture/écriture boolean.

**Renvoie :**
boolean

### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```

Détermine si la zone de texte est centrée à l'intérieur d'une cellule. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```

Obtient la première colonne de la cellule. Lecture seule [IColumn](../../com.aspose.slides/icolumn).

**Renvoie :**
[IColumn](../../com.aspose.slides/icolumn)

### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```

Obtient la première ligne de la cellule. Lecture seule [IRow](../../com.aspose.slides/irow).

**Renvoie :**
[IRow](../../com.aspose.slides/irow)

### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```

Renvoie le nombre de colonnes de la grille du tableau parent qui doivent être englobées par la cellule actuelle. Cette propriété permet aux cellules d'avoir l'apparence d'être fusionnées, car elles englobent les limites verticales d'autres cellules du tableau. Lecture seule int.

**Renvoie :**
int

### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```

Renvoie le nombre de lignes qu'une cellule fusionnée occupe. Ceci est utilisé en combinaison avec l'attribut vMerge sur d'autres cellules afin de spécifier la cellule de départ d'une fusion horizontale. Lecture seule int.

**Renvoie :**
int

### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Renvoie le cadre de texte d'une cellule. Lecture seule [ITextFrame](../../com.aspose.slides/itextframe).

**Renvoie :**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTable() {#getTable--}
```
public abstract ITable getTable()
```

Renvoie l'objet Table parent d'une cellule. Lecture seule [ITable](../../com.aspose.slides/itable).

**Renvoie :**
[ITable](../../com.aspose.slides/itable)

### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```

Renvoie vrai si la cellule est fusionnée avec une cellule adjacente, faux sinon. Lecture seule boolean.

**Renvoie :**
boolean

### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```

Renvoie l'objet CellFormat qui contient les propriétés de formatage pour cette cellule. Lecture seule [ICellFormat](../../com.aspose.slides/icellformat).

**Renvoie :**
[ICellFormat](../../com.aspose.slides/icellformat)

### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```

Divise la cellule en deux cellules par indice de colonne.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice de la colonne. |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```

Divise la cellule en deux cellules par indice de ligne.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice de la ligne. |

### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```

Divise la cellule par hauteur.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| height | double | Hauteur de la ligne. |

### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```

Divise la cellule par largeur.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | double | Largeur de la colonne. |