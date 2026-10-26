---
title: IMathMatrix
second_title: Référence de l'API Aspose.Slides pour Java
description: Spécifie l'objet Matrix composé d'éléments enfants disposés sur une ou plusieurs lignes et colonnes.
type: docs
url: /fr/com.aspose.slides/imathmatrix/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Spécifie l'objet Matrix, composé d'éléments enfants disposés sur une ou plusieurs lignes et colonnes. Il est important de noter que les matrices n'ont pas de délimiteurs intégrés. Pour placer la matrice entre parenthèses, vous devez utiliser l'objet délimiteur (IMathDelimiter). Des arguments nuls peuvent être utilisés pour créer des espaces vides dans les matrices.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | Éléments de la matrice |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Éléments de la matrice |
| [getRowCount()](#getRowCount--) | Nombre de lignes dans la matrice |
| [getColumnCount()](#getColumnCount--) | Nombre de colonnes dans la matrice |
| [getHidePlaceholders()](#getHidePlaceholders--) | Masquer les espaces réservés pour les éléments vides de la matrice Par défaut : false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Masquer les espaces réservés pour les éléments vides de la matrice Par défaut : false |
| [getBaseJustification()](#getBaseJustification--) | Spécifie l'alignement vertical par rapport au texte environnant. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Spécifie l'alignement vertical par rapport au texte environnant. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Largeur minimale de colonne en twips (1/20e d'un point). L'espacement de l'écart (également appelé \u201cColumn Gap\u201d ou \u201cGap Width\u201d) est ajouté à MinColumnWidth pour déterminer l'espacement total des colonnes de la matrice (distance entre les mêmes bords de colonnes différentes). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Largeur minimale de colonne en twips (1/20e d'un point). L'espacement de l'écart (également appelé \u201cColumn Gap\u201d ou \u201cGap Width\u201d) est ajouté à MinColumnWidth pour déterminer l'espacement total des colonnes de la matrice (distance entre les mêmes bords de colonnes différentes). |
| [getColumnGapRule()](#getColumnGapRule--) | Le type d'espacement horizontal entre les colonnes d'une matrice ; les unités d'espacement horizontal peuvent être des ems ou des points (stockés en twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Le type d'espacement horizontal entre les colonnes d'une matrice ; les unités d'espacement horizontal peuvent être des ems ou des points (stockés en twips). |
| [getColumnGap()](#getColumnGap--) | La valeur de l'espacement horizontal entre les colonnes d'une matrice ; si ColumnGapRule est défini sur 3 ("Exactly"), l'unité est interprétée en twips (1/20e d'un point). Si ColumnGapRule est défini sur 4 ("Multiple"), l'unité est interprétée comme un nombre d'incréments de 0,5 em. |
| [setColumnGap(long value)](#setColumnGap-long-) | La valeur de l'espacement horizontal entre les colonnes d'une matrice ; si ColumnGapRule est défini sur 3 ("Exactly"), l'unité est interprétée en twips (1/20e d'un point). Si ColumnGapRule est défini sur 4 ("Multiple"), l'unité est interprétée comme un nombre d'incréments de 0,5 em. |
| [getRowGapRule()](#getRowGapRule--) | Le type d'espacement vertical entre les lignes d'une matrice ; les unités d'espacement vertical peuvent être des lignes ou des points (stockés en twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Le type d'espacement vertical entre les lignes d'une matrice ; les unités d'espacement vertical peuvent être des lignes ou des points (stockés en twips). |
| [getRowGap()](#getRowGap--) | La valeur de l'espacement vertical entre les lignes d'une matrice ; si RowGapRule est défini sur 3 ("Exactly"), l'unité est interprétée en twips (1/20e d'un point). Si RowGapRule est défini sur 4 ("Multiple"), l'unité est interprétée comme des demi-lignes. |
| [setRowGap(long value)](#setRowGap-long-) | La valeur de l'espacement vertical entre les lignes d'une matrice ; si RowGapRule est défini sur 3 ("Exactly"), l'unité est interprétée en twips (1/20e d'un point). Si RowGapRule est défini sur 4 ("Multiple"), l'unité est interprétée comme des demi-lignes. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Obtenir l'alignement horizontal de la colonne spécifiée |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Définir l'alignement horizontal de la colonne spécifiée |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Définir l'alignement horizontal des colonnes spécifiées |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Insérer une nouvelle ligne avant celle spécifiée. Initialement, tous les éléments de la nouvelle ligne sont nuls. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Insérer une nouvelle ligne après celle spécifiée. Initialement, tous les éléments de la nouvelle ligne sont nuls. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Supprime la ligne spécifiée |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Insérer une nouvelle colonne avant celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont nuls. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Insérer une nouvelle colonne après celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont nuls. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Supprime la colonne spécifiée |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

Éléments de la matrice

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
| row | int | L'index basé sur zéro de la ligne dont on veut obtenir l'élément |
| column | int | L'index basé sur zéro de la colonne dont on veut obtenir l'élément |

**Retour :**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement

### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```

Éléments de la matrice

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
| row | int | L'index basé sur zéro de la ligne dont on veut obtenir l'élément |
| column | int | L'index basé sur zéro de la colonne dont on veut obtenir l'élément |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
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
public abstract int getColumnCount()
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
public abstract boolean getHidePlaceholders()
```

Masquer les espaces réservés pour les éléments vides de la matrice Par défaut : false

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
public abstract void setHidePlaceholders(boolean value)
```

Masquer les espaces réservés pour les éléments vides de la matrice Par défaut : false

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
public abstract int getBaseJustification()
```

Spécifie l'alignement vertical par rapport au texte environnant. Les valeurs possibles sont top, bottom et center. Par défaut : Center

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
public abstract void setBaseJustification(int value)
```

Spécifie l'alignement vertical par rapport au texte environnant. Les valeurs possibles sont top, bottom et center. Par défaut : Center

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
public abstract long getMinColumnWidth()
```

Largeur minimale de colonne en twips (1/20e d'un point). L'espacement de l'écart (également appelé \u201cColumn Gap\u201d ou \u201cGap Width\u201d) est ajouté à MinColumnWidth pour déterminer l'espacement total des colonnes de la matrice (distance entre les mêmes bords de colonnes différentes). Par défaut : 0.

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
public abstract void setMinColumnWidth(long value)
```

Largeur minimale de colonne en twips (1/20e d'un point). L'espacement de l'écart (également appelé \u201cColumn Gap\u201d ou \u201cGap Width\u201d) est ajouté à MinColumnWidth pour déterminer l'espacement total des colonnes de la matrice (distance entre les mêmes bords de colonnes différentes). Par défaut : 0.

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
public abstract int getColumnGapRule()
```

Le type d'espacement horizontal entre les colonnes d'une matrice ; les unités d'espacement horizontal peuvent être des ems ou des points (stockés en twips). Par défaut : SingleSpacingGap (0)

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
public abstract void setColumnGapRule(int value)
```

Le type d'espacement horizontal entre les colonnes d'une matrice ; les unités d'espacement horizontal peuvent être des ems ou des points (stockés en twips). Par défaut : SingleSpacingGap (0)

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
public abstract long getColumnGap()
```

La valeur de l'espacement horizontal entre les colonnes d'une matrice ; si ColumnGapRule est défini sur 3 ("Exactly"), l'unité est interprétée en twips (1/20e d'un point). Si ColumnGapRule est défini sur 4 ("Multiple"), l'unité est interprétée comme un nombre d'incréments de 0,5 em. Dans les autres cas, ignoré. Par défaut : 0

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
public abstract void setColumnGap(long value)
```

La valeur de l'espacement horizontal entre les colonnes d'une matrice ; si ColumnGapRule est défini sur 3 ("Exactly"), l'unité est interprétée en twips (1/20e d'un point). Si ColumnGapRule est défini sur 4 ("Multiple"), l'unité est interprétée comme un nombre d'incréments de 0,5 em. Dans les autres cas, ignoré. Par défaut : 0

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
public abstract int getRowGapRule()
```

Le type d'espacement vertical entre les lignes d'une matrice ; les unités d'espacement vertical peuvent être des lignes ou des points (stockés en twips). Par défaut : SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Retour :**
int

### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```

Le type d'espacement vertical entre les lignes d'une matrice ; les unités d'espacement vertical peuvent être des lignes ou des points (stockés en twips). Par défaut : SingleSpacingGap (0)

--------------------

> ```
> Example:
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
public abstract long getRowGap()
```

La valeur de l'espacement vertical entre les lignes d'une matrice ; si RowGapRule est défini sur 3 ("Exactly"), l'unité est interprétée en twips (1/20e d'un point). Si RowGapRule est défini sur 4 ("Multiple"), l'unité est interprétée comme des demi-lignes. Par défaut : 0

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
public abstract void setRowGap(long value)
```

La valeur de l'espacement vertical entre les lignes d'une matrice ; si RowGapRule est défini sur 3 ("Exactly"), l'unité est interprétée en twips (1/20e d'un point). Si RowGapRule est défini sur 4 ("Multiple"), l'unité est interprétée comme des demi-lignes. Par défaut : 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Paramètres :**
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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index de colonne basé sur zéro |

**Retour :**
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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index de colonne basé sur zéro |
| val | int | Nouvelle valeur de l'alignement horizontal de la colonne spécifiée |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Définir l'alignement horizontal des colonnes spécifiées

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index de la première colonne dont on veut définir l'alignement |
| columnsCount | long | Nombre de colonnes pour lesquelles définir l'alignement |
| val | int | Nouvelle valeur de l'alignement horizontal de la colonne spécifiée |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

Insérer une nouvelle ligne avant celle spécifiée. Initialement, tous les éléments de la nouvelle ligne sont nuls.

--------------------

> ```
> Example:
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
public abstract void insertRowAfter(int rowIndex)
```

Insérer une nouvelle ligne après celle spécifiée. Initialement, tous les éléments de la nouvelle ligne sont nuls.

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| rowIndex | int | L'index basé sur zéro de la ligne à supprimer. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

Insérer une nouvelle colonne avant celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont nuls.

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
public abstract void insertColumnAfter(int columnIndex)
```

Insérer une nouvelle colonne après celle spécifiée. Initialement, tous les éléments de la nouvelle colonne sont nuls.

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
public abstract void deleteColumn(int columnIndex)
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