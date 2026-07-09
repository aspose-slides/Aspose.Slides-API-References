---
title: MathMatrix
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Spécifie l'objet Matrix composé d'éléments enfants disposés sur une ou plusieurs lignes et colonnes.
type: docs
url: /fr/com.aspose.slides/mathmatrix/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

Spécifie l'objet Matrix, composé d'éléments enfants disposés sur une ou plusieurs lignes et colonnes. Il est important de noter que les matrices n'ont pas de délimiteurs intégrés. Pour placer la matrice entre crochets, vous devez utiliser l'objet délimiteur (IMathDelimiter). Des arguments null peuvent être utilisés pour créer des espaces dans les matrices.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | Initializes a new instance of the MathMatrix class. |
## Methods

| Method | Description |
| --- | --- |
| [getRowCount()](#getRowCount--) | Number of rows in the matrix |
| [getColumnCount()](#getColumnCount--) | Number of columns in the matrix |
| [getHidePlaceholders()](#getHidePlaceholders--) | Hide the placeholders for empty matrix elements Default: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Hide the placeholders for empty matrix elements Default: false |
| [getBaseJustification()](#getBaseJustification--) | Specifies the vertical justification respect to surrounding text. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Specifies the vertical justification respect to surrounding text. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as \u201cColumn Gap\u201d or \u201cGap Width\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as \u201cColumn Gap\u201d or \u201cGap Width\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). |
| [getColumnGapRule()](#getColumnGapRule--) | The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). |
| [getColumnGap()](#getColumnGap--) | The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. |
| [setColumnGap(long value)](#setColumnGap-long-) | The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. |
| [getRowGapRule()](#getRowGapRule--) | The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). |
| [getRowGap()](#getRowGap--) | The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. |
| [setRowGap(long value)](#setRowGap-long-) | The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Element of matrix |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Element of matrix |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Get the horizontal alignment of the specified column |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Set the horizontal alignment of the specified column |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Set the horizontal alignment of the specified columns |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Insert a new row before the specified one Initially all elements in the new row are null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Insert a new row after the specified one Initially all elements in the new row are null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Deletes the specified row |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Insert a new column before the specified one Initially all elements in the new column are null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Insert a new column after the specified one Initially all elements in the new column are null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Deletes the specified column |
| [getChildren()](#getChildren--) | Get children elements |
### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

Initializes a new instance of the MathMatrix class.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowCount | int | row count |
| columnCount | int | column count |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
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
public final int getColumnCount()
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
public final boolean getHidePlaceholders()
```

Hide the placeholders for empty matrix elements Default: false

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
public final void setHidePlaceholders(boolean value)
```

Hide the placeholders for empty matrix elements Default: false

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
public final int getBaseJustification()
```

Specifies the vertical justification respect to surrounding text. Possible values are top, bottom, and center. Default: Center

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
public final void setBaseJustification(int value)
```

Spécifie la justification verticale par rapport au texte environnant. Les valeurs possibles sont haut, bas et centre. Par défaut : Centre

--------------------

> ```
> Exemple:
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
public final long getMinColumnWidth()
```

Largeur minimale de colonne en twips (1/20e de point). L’espacement (également appelé « Column Gap » ou « Gap Width ») est ajouté à MinColumnWidth pour déterminer l’espacement total des colonnes de la matrice (distance entre les mêmes bords de colonnes différentes). Valeur par défaut : 0.

--------------------

> ```
> Exemple:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Returns:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public final void setMinColumnWidth(long value)
```

Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as \u201cColumn Gap\u201d or \u201cGap Width\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). Default: 0.

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
public final int getColumnGapRule()
```

Le type d'espacement horizontal entre les colonnes d'une matrice ; les unités d'espacement horizontal peuvent être des ems ou des points (stockés en twips). Valeur par défaut : SingleSpacingGap (0)

--------------------

> ```
> Exemple:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Returns:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public final void setColumnGapRule(int value)
```

Le type d'espacement horizontal entre les colonnes d'une matrice ; les unités d'espacement horizontal peuvent être des ems ou des points (stockés en twips). Valeur par défaut : SingleSpacingGap (0)

--------------------

> ```
> Exemple:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public final long getColumnGap()
```

La valeur de l'espacement horizontal entre les colonnes d'une matrice ; si la ColumnGapRule est définie sur 3 (« Exactly »), alors l'unité est interprétée en twips (1/20e de point). Si la ColumnGapRule est définie sur 4 (« Multiple »), alors l'unité est interprétée comme un nombre d'incréments de 0,5 em. Dans les autres cas, ignoré. Valeur par défaut : 0

--------------------

> ```
> Exemple:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Returns:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public final void setColumnGap(long value)
```

La valeur de l'espacement horizontal entre les colonnes d'une matrice ; si la ColumnGapRule est définie sur 3 ("Exactly"), l'unité est interprétée en twips (1/20e de point) si la ColumnGapRule est définie sur 4 ("Multiple"), l'unité est interprétée comme un nombre d'incréments de 0,5 em. Dans les autres cas, ignoré. Valeur par défaut : 0

--------------------

> ```
> Exemple:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public final int getRowGapRule()
```

Le type d'espacement vertical entre les lignes d'une matrice ; les unités d'espacement vertical peuvent être des lignes ou des points (stockés en twips). Valeur par défaut : SingleSpacingGap (0)

--------------------

> ```
> Exemple:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Returns:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public final void setRowGapRule(int value)
```

Le type d'espacement vertical entre les lignes d'une matrice ; les unités d'espacement vertical peuvent être des lignes ou des points (stockés en twips). Valeur par défaut : SingleSpacingGap (0)

--------------------

> ```
> Exemple:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public final long getRowGap()
```

The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. Default: 0

--------------------

> ```
> Exemple:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Returns:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public final void setRowGap(long value)
```
La valeur de l'espacement vertical entre les lignes d'une matrice ; si la RowGapRule est définie sur 3 (« Exactly »), l'unité est interprétée en twips (1/20e de point) si la RowGapRule est définie sur 4 (« Multiple »), l'unité est interprétée comme des demi-lignes. Valeur par défaut : 0

--------------------

> ```
> Exemple:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Paramètres:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```

Élément de la matrice

--------------------

> ```
> Exemple:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | L'indice basé sur zéro de la ligne à récupérer |
| column | int | L'indice basé sur zéro de la colonne à récupérer |

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```

Élément de la matrice

--------------------

> ```
> Exemple:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | L'indice basé sur zéro de la ligne à récupérer |
| column | int | L'indice basé sur zéro de la colonne à récupérer |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**Returns:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
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
int - Horizontal Alignment of specified column
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```
Définit l'alignement horizontal de la colonne spécifiée

--------------------

> ```
> Exemple:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Indice de colonne basé sur zéro |
| val | int | Nouvelle valeur de l'alignement horizontal de la colonne spécifiée |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Définit l'alignement horizontal des colonnes spécifiées

--------------------

> ```
> Exemple:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Indice de colonne basé sur zéro de la première colonne à définir l'alignement |
| columnsCount | long | Nombre de colonnes pour spécifier l'alignement |
| val | int | Nouvelle valeur de l'alignement horizontal des colonnes spécifiées |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```
Insère une nouvelle ligne avant celle spécifiée. Initialement, tous les éléments de la nouvelle ligne sont null.

--------------------

> ```
> Exemple:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | Index of the row before which to insert a new one |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

Insère une nouvelle ligne après la ligne spécifiée. Initialement tous les éléments de la nouvelle ligne sont null.

--------------------

> ```
> Exemple:
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
public final void deleteRow(int rowIndex)
```

Supprime la ligne spécifiée

--------------------

> ```
> Exemple:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | L'indice basé sur zéro de la ligne à supprimer. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```
Insère une nouvelle colonne avant celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont null.

--------------------

> ```
> Exemple:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index of the column before which to insert a new one |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

Insère une nouvelle colonne après celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont null.

--------------------

> ```
> Example:
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
public final void deleteColumn(int columnIndex)
```

Supprime la colonne spécifiée

--------------------

> ```
> Exemple:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | L'indice basé sur zéro de la colonne à supprimer. |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()


Obtenir les éléments enfants

**Renvoie :**
com.aspose.slides.IMathElement[]