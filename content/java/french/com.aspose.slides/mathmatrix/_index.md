---
title: MathMatrix
second_title: Référence de l'API Aspose.Slides pour Java
description: Spécifie l'objet Matrix composé d'éléments enfants disposés en une ou plusieurs lignes et colonnes.
type: docs
url: /fr/com.aspose.slides/mathmatrix/
---
**Héritage:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

Spécifie l'objet Matrix, composé d'éléments enfants disposés en une ou plusieurs lignes et colonnes. Il est important de noter que les matrices n'ont pas de délimiteurs intégrés. Pour placer la matrice entre crochets, vous devez utiliser l'objet délimiteur (IMathDelimiter). Des arguments null peuvent être utilisés pour créer des espaces dans les matrices.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | Initialise une nouvelle instance de la classe MathMatrix. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRowCount()](#getRowCount--) | Nombre de lignes dans la matrice |
| [getColumnCount()](#getColumnCount--) | Nombre de colonnes dans la matrice |
| [getHidePlaceholders()](#getHidePlaceholders--) | Masquer les espaces réservés pour les éléments de matrice vides Valeur par défaut : false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Masquer les espaces réservés pour les éléments de matrice vides Valeur par défaut : false |
| [getBaseJustification()](#getBaseJustification--) | Spécifie la justification verticale par rapport au texte environnant. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Spécifie la justification verticale par rapport au texte environnant. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Largeur minimale de colonne en twips (1/20e de point) L'espacement de l'écart (également appelé \\u201cColumn Gap\\u201d ou \\u201cGap Width\\u201d) est ajouté à MinColumnWidth pour déterminer l'espacement total des colonnes de la matrice (distance entre les mêmes bords de différentes colonnes). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Largeur minimale de colonne en twips (1/20e de point) L'espacement de l'écart (également appelé \\u201cColumn Gap\\u201d ou \\u201cGap Width\\u201d) est ajouté à MinColumnWidth pour déterminer l'espacement total des colonnes de la matrice (distance entre les mêmes bords de différentes colonnes). |
| [getColumnGapRule()](#getColumnGapRule--) | Le type d'espacement horizontal entre les colonnes d'une matrice ; les unités d'espacement horizontal peuvent être en ems ou en points (stockés en twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Le type d'espacement horizontal entre les colonnes d'une matrice ; les unités d'espacement horizontal peuvent être en ems ou en points (stockés en twips). |
| [getColumnGap()](#getColumnGap--) | La valeur de l'espacement horizontal entre les colonnes d'une matrice ; si ColumnGapRule vaut 3 (\"Exactly\"), l'unité est interprétée en twips (1/20e de point). Si ColumnGapRule vaut 4 (\"Multiple\"), l'unité est interprétée comme un nombre d'incréments de 0,5 em. |
| [setColumnGap(long value)](#setColumnGap-long-) | La valeur de l'espacement horizontal entre les colonnes d'une matrice ; si ColumnGapRule vaut 3 (\"Exactly\"), l'unité est interprétée en twips (1/20e de point). Si ColumnGapRule vaut 4 (\"Multiple\"), l'unité est interprétée comme un nombre d'incréments de 0,5 em. |
| [getRowGapRule()](#getRowGapRule--) | Le type d'espacement vertical entre les lignes d'une matrice ; les unités d'espacement vertical peuvent être des lignes ou des points (stockés en twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Le type d'espacement vertical entre les lignes d'une matrice ; les unités d'espacement vertical peuvent être des lignes ou des points (stockés en twips). |
| [getRowGap()](#getRowGap--) | La valeur de l'espacement vertical entre les lignes d'une matrice ; si RowGapRule vaut 3 (\"Exactly\"), l'unité est interprétée en twips (1/20e de point). Si RowGapRule vaut 4 (\"Multiple\"), l'unité est interprétée comme des demi-lignes. |
| [setRowGap(long value)](#setRowGap-long-) | La valeur de l'espacement vertical entre les lignes d'une matrice ; si RowGapRule vaut 3 (\"Exactly\"), l'unité est interprétée en twips (1/20e de point). Si RowGapRule vaut 4 (\"Multiple\"), l'unité est interprétée comme des demi-lignes. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Élément de la matrice |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Élément de la matrice |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propriétés du caractère de contrôle |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Obtenir l'alignement horizontal de la colonne spécifiée |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Définir l'alignement horizontal de la colonne spécifiée |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Définir l'alignement horizontal des colonnes spécifiées |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Insérer une nouvelle ligne avant celle spécifiée. Initialement, tous les éléments de la nouvelle ligne sont null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Insérer une nouvelle ligne après celle spécifiée. Initialement, tous les éléments de la nouvelle ligne sont null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Supprime la ligne spécifiée |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Insérer une nouvelle colonne avant celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Insérer une nouvelle colonne après celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Supprime la colonne spécifiée |
| [getChildren()](#getChildren--) | Obtenir les éléments enfants |

### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

Initialise une nouvelle instance de la classe MathMatrix.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| rowCount | int | nombre de lignes |
| columnCount | int | nombre de colonnes |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
```

Nombre de lignes dans la matrice

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Retour :**
int
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

Nombre de colonnes dans la matrice

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Retour :**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public final boolean getHidePlaceholders()
```

Masquer les espaces réservés pour les éléments de matrice vides Valeur par défaut : false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Retour :**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public final void setHidePlaceholders(boolean value)
```

Masquer les espaces réservés pour les éléments de matrice vides Valeur par défaut : false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

Spécifie la justification verticale par rapport au texte environnant. Les valeurs possibles sont top, bottom et center. Valeur par défaut : Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Retour :**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

Spécifie la justification verticale par rapport au texte environnant. Les valeurs possibles sont top, bottom et center. Valeur par défaut : Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public final long getMinColumnWidth()
```

Largeur minimale de colonne en twips (1/20e de point) L'espacement de l'écart (également appelé \\u201cColumn Gap\\u201d ou \\u201cGap Width\\u201d) est ajouté à MinColumnWidth pour déterminer l'espacement total des colonnes de la matrice (distance entre les mêmes bords de différentes colonnes). Valeur par défaut : 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Retour :**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public final void setMinColumnWidth(long value)
```

Largeur minimale de colonne en twips (1/20e de point) L'espacement de l'écart (également appelé \\u201cColumn Gap\\u201d ou \\u201cGap Width\\u201d) est ajouté à MinColumnWidth pour déterminer l'espacement total des colonnes de la matrice (distance entre les mêmes bords de différentes colonnes). Valeur par défaut : 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public final int getColumnGapRule()
```

Le type d'espacement horizontal entre les colonnes d'une matrice ; les unités d'espacement horizontal peuvent être en ems ou en points (stockés en twips). Valeur par défaut : SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Retour :**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public final void setColumnGapRule(int value)
```

Le type d'espacement horizontal entre les colonnes d'une matrice ; les unités d'espacement horizontal peuvent être en ems ou en points (stockés en twips). Valeur par défaut : SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public final long getColumnGap()
```

La valeur de l'espacement horizontal entre les colonnes d'une matrice ; si ColumnGapRule vaut 3 (\"Exactly\"), l'unité est interprétée en twips (1/20e de point). Si ColumnGapRule vaut 4 (\"Multiple\"), l'unité est interprétée comme un nombre d'incréments de 0,5 em. Dans les autres cas, ignoré. Valeur par défaut : 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Retour :**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public final void setColumnGap(long value)
```

La valeur de l'espacement horizontal entre les colonnes d'une matrice ; si ColumnGapRule vaut 3 (\"Exactly\"), l'unité est interprétée en twips (1/20e de point). Si ColumnGapRule vaut 4 (\"Multiple\"), l'unité est interprétée comme un nombre d'incréments de 0,5 em. Dans les autres cas, ignoré. Valeur par défaut : 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Paramètres :**
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

**Retour :**
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

La valeur de l'espacement vertical entre les lignes d'une matrice ; si RowGapRule vaut 3 (\"Exactly\"), l'unité est interprétée en twips (1/20e de point). Si RowGapRule vaut 4 (\"Multiple\"), l'unité est interprétée comme des demi-lignes. Valeur par défaut : 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Retour :**
long
### setRowGap(long value) {#setRowGap-long-}
```
public final void setRowGap(long value)
```

La valeur de l'espacement vertical entre les lignes d'une matrice ; si RowGapRule vaut 3 (\"Exactly\"), l'unité est interprétée en twips (1/20e de point). Si RowGapRule vaut 4 (\"Multiple\"), l'unité est interprétée comme des demi-lignes. Valeur par défaut : 0

--------------------

> ```
> Exemple :
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```

Élément de la matrice

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| row | int | L'index basé sur zéro de la ligne à obtenir |
| column | int | L'index basé sur zéro de la colonne à obtenir |

**Retour :**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```

Élément de la matrice

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| row | int | L'index basé sur zéro de la ligne à obtenir |
| column | int | L'index basé sur zéro de la colonne à obtenir |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Propriétés du caractère de contrôle

**Retour :**
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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index de colonne basé sur zéro |

**Retour :**
int - Alignement horizontal de la colonne spécifiée
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

Définir l'alignement horizontal de la colonne spécifiée

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index de colonne basé sur zéro |
| val | int | Nouvelle valeur de l'alignement horizontal de la colonne spécifiée |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Définir l'alignement horizontal des colonnes spécifiées

--------------------

> ```
> Exemple:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index basé sur zéro de la première colonne à aligner |
| columnsCount | long | Nombre de colonnes dont l'alignement doit être défini |
| val | int | Nouvelle valeur de l'alignement horizontal de la colonne spécifiée |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

Insérer une nouvelle ligne avant celle spécifiée. Initialement, tous les éléments de la nouvelle ligne sont null.

--------------------

> ```
> Exemple:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| rowIndex | int | Index de la ligne avant laquelle insérer une nouvelle ligne |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

Insérer une nouvelle ligne après celle spécifiée. Initialement, tous les éléments de la nouvelle ligne sont null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| rowIndex | int | Index de la ligne après laquelle insérer une nouvelle ligne |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```

Supprime la ligne spécifiée

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| rowIndex | int | L'index basé sur zéro de la ligne à supprimer. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

Insérer une nouvelle colonne avant celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index de la colonne avant laquelle insérer une nouvelle colonne |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

Insérer une nouvelle colonne après celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index de la colonne après laquelle insérer une nouvelle colonne |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```

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
| columnIndex | int | L'index basé sur zéro de la colonne à supprimer. |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Obtenir les éléments enfants

**Retour :**
com.aspose.slides.IMathElement[]