---
title: IMathMatrix
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Spécifie l'objet Matrix composé d'éléments enfants disposés sur une ou plusieurs lignes et colonnes.
type: docs
url: /fr/com.aspose.slides/imathmatrix/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Spécifie l'objet Matrix, composé d'éléments enfants disposés sur une ou plusieurs lignes et colonnes. Il est important de noter que les matrices n'ont pas de délimiteurs intégrés. Pour placer la matrice entre crochets, vous devez utiliser l'objet délimiteur (IMathDelimiter). Des arguments nuls peuvent être utilisés pour créer des espaces dans les matrices.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | Elements of matrix |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Elements of matrix |
| [getRowCount()](#getRowCount--) | Number of rows in the matrix |
| [getColumnCount()](#getColumnCount--) | Number of columns in the matrix |
| [getHidePlaceholders()](#getHidePlaceholders--) | Hide the placeholders for empty matrix elements Default: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Hide the placeholders for empty matrix elements Default: false |
| [getBaseJustification()](#getBaseJustification--) | Specifies the vertical justification respect to surrounding text. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Specifies the vertical justification respect to surrounding text. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). |
| [getColumnGapRule()](#getColumnGapRule--) | The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). |
| [getColumnGap()](#getColumnGap--) | The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. |
| [setColumnGap(long value)](#setColumnGap-long-) | The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. |
| [getRowGapRule()](#getRowGapRule--) | The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). |
| [getRowGap()](#getRowGap--) | The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. |
| [setRowGap(long value)](#setRowGap-long-) | The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Get the horizontal alignment of the specified column |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Set the horizontal alignment of the specified column |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Set the horizontal alignment of the specified columns |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Insert a new row before the specified one Initially all elements in the new row are null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Insert a new row after the specified one Initially all elements in the new row are null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Deletes the specified row |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Insert a new column before the specified one Initially all elements in the new column are null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Insert a new column after the specified one Initially all elements in the new column are null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Deletes the specified column |
### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

Elements of matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```

Elements of matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
```

Number of rows in the matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Returns:**
int
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Number of columns in the matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Returns:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public abstract boolean getHidePlaceholders()
```

Masquer les espaces réservés pour les éléments de matrice vides Valeur par défaut : false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Returns:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```

Masquer les espaces réservés pour les éléments de matrice vides Valeur par défaut : false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

Spécifie la justification verticale par rapport au texte environnant. Les valeurs possibles sont top, bottom, et center. Valeur par défaut : Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Returns:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Spécifie la justification verticale par rapport au texte environnant. Les valeurs possibles sont top, bottom et center. Valeur par défaut : Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public abstract long getMinColumnWidth()
```

Largeur minimale de colonne en twips (1/20e d'un point) L'espacement entre les colonnes (également appelé \\u201cColumn Gap\\u201d ou \\u201cGap Width\\u201d) est ajouté à MinColumnWidth pour déterminer l'espacement total des colonnes de la matrice (distance entre les mêmes bords de différentes colonnes). Valeur par défaut: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Returns:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```

Largeur minimale de colonne en twips (1/20e d'un point) L'espacement entre les colonnes (également appelé \u201cColumn Gap\u201d ou \u201cGap Width\u201d) est ajouté à MinColumnWidth pour déterminer l'espacement total des colonnes de la matrice (distance entre les mêmes bords de différentes colonnes). Valeur par défaut : 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public abstract int getColumnGapRule()
```
The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). Default: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Returns:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public abstract void setColumnGapRule(int value)
```
The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). Default: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public abstract long getColumnGap()
```

The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. In other cases ignored. Default: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Returns:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public abstract void setColumnGap(long value)
```

La valeur de l'espacement horizontal entre les colonnes d'une matrice ; si le ColumnGapRule est réglé sur 3 (« Exactly »), l'unité est interprétée comme des twips (1/20e d'un point). Si le ColumnGapRule est réglé sur 4 (« Multiple »), l'unité est interprétée comme un nombre d'incréments de 0,5 em. Dans les autres cas, ignoré. Valeur par défaut : 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public abstract int getRowGapRule()
```

Le type d'espacement vertical entre les lignes d'une matrice ; les unités d'espacement vertical peuvent être des lignes ou des points (stockés en twips). Valeur par défaut : SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Returns:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```

Le type d'espacement vertical entre les lignes d'une matrice ; les unités d'espacement vertical peuvent être des lignes ou des points (stockés en twips). Valeur par défaut : SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public abstract long getRowGap()
```

La valeur de l'espacement vertical entre les lignes d'une matrice ; si le RowGapRule est réglé sur 3 ("Exactly"), l'unité est interprétée comme des twips (1/20e d'un point). Si le RowGapRule est réglé sur 4 ("Multiple"), l'unité est interprétée comme des demi-lignes. Valeur par défaut : 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Returns:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public abstract void setRowGap(long value)
```
La valeur de l'espacement vertical entre les lignes d'une matrice ; si le RowGapRule est réglé sur 3 (« Exactly »), alors l'unité est interprétée comme des twips (1/20e d'un point). Si le RowGapRule est réglé sur 4 (« Multiple »), alors l'unité est interprétée comme des demi-lignes. Valeur par défaut : 0

--------------------

> ```
> Exemple:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

Obtenir l'alignement horizontal de la colonne spécifiée

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Indice de colonne basé sur zéro |

**Returns:**
int - Alignement horizontal de la colonne spécifiée
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```
Définir l'alignement horizontal de la colonne spécifiée

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Zero-based column index |
| val | int | New value of horizontal alignment of specified column |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Set the horizontal alignment of the specified columns

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Zero-based index of the first column to set alignment |
| columnsCount | long | The number of columns to specify the alignment |
| val | int | New value of horizontal alignment of specified column |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

Insérer une nouvelle ligne avant celle spécifiée. Tous les éléments de la nouvelle ligne sont initialement nuls.

--------------------

> ```
> Exemple:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | Index de la ligne avant laquelle insérer une nouvelle |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

Insérer une nouvelle ligne après celle spécifiée. Tous les éléments de la nouvelle ligne sont initialement nuls.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | Index of the row after which to insert a new one |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```
Supprime la ligne spécifiée

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | The zero-based index of the row to delete. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```
Insérez une nouvelle colonne avant celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont nuls.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index of the column before which to insert a new one |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

Insérer une nouvelle colonne après celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont nuls.

--------------------

> ```
> Exemple:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index of the column after which to insert a new one |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)

Supprime la colonne spécifiée

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | int | L'index de la colonne à supprimer, basé sur zéro. |