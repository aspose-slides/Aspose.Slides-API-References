---
title: Table
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente un tableau sur une diapositive.
type: docs
url: /fr/com.aspose.slides/table/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Toutes les interfaces implémentées :**
[com.aspose.slides.ITable](../../com.aspose.slides/itable)
```
public final class Table extends GraphicalObject implements ITable
```

Représente un tableau sur une diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Renvoie la cellule aux indices de colonne et de ligne spécifiés. |
| [getRows()](#getRows--) | Renvoie la collection de lignes. |
| [getColumns()](#getColumns--) | Renvoie la collection de colonnes. |
| [getTableFormat()](#getTableFormat--) | Renvoie l'objet TableFormat qui contient les propriétés de mise en forme de ce tableau. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Fusionne les cellules voisines. |
| [getStylePreset()](#getStylePreset--) | Obtient ou définit le style de tableau intégré. |
| [setStylePreset(int value)](#setStylePreset-int-) | Obtient ou définit le style de tableau intégré. |
| [getRightToLeft()](#getRightToLeft--) | Détermine si le tableau a un sens de lecture de droite à gauche. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Détermine si le tableau a un sens de lecture de droite à gauche. |
| [getFirstRow()](#getFirstRow--) | Détermine si la première ligne d'un tableau doit être dessinée avec une mise en forme spéciale. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Détermine si la première ligne d'un tableau doit être dessinée avec une mise en forme spéciale. |
| [getFirstCol()](#getFirstCol--) | Détermine si la première colonne d'un tableau doit être dessinée avec une mise en forme spéciale. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Détermine si la première colonne d'un tableau doit être dessinée avec une mise en forme spéciale. |
| [getLastRow()](#getLastRow--) | Détermine si la dernière ligne d'un tableau doit être dessinée avec une mise en forme spéciale. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Détermine si la dernière ligne d'un tableau doit être dessinée avec une mise en forme spéciale. |
| [getLastCol()](#getLastCol--) | Détermine si la dernière colonne d'un tableau doit être dessinée avec une mise en forme spéciale. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Détermine si la dernière colonne d'un tableau doit être dessinée avec une mise en forme spéciale. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Détermine si les lignes paires doivent être dessinées avec une mise en forme différente. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Détermine si les lignes paires doivent être dessinées avec une mise en forme différente. |
| [getVerticalBanding()](#getVerticalBanding--) | Détermine si les colonnes paires doivent être dessinées avec une mise en forme différente. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Détermine si les colonnes paires doivent être dessinées avec une mise en forme différente. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Définit les propriétés de format de portion définies pour toutes les portions des cellules du tableau. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Définit les propriétés de format de paragraphe définies pour tous les paragraphes des cellules du tableau. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Définit les propriétés de format de cadre de texte définies pour tous les cadres de texte des cellules du tableau. |
| [getFillFormat()](#getFillFormat--) | Renvoie un objet TableFormat.FillFormat contenant le format de remplissage pour le tableau. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

Renvoie la cellule aux indices de colonne et de ligne spécifiés. Lecture seule [Cell](../../com.aspose.slides/cell).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Renvoie :**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

Renvoie la collection de lignes. Lecture seule [IRowCollection](../../com.aspose.slides/irowcollection).

**Renvoie :**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

Renvoie la collection de colonnes. Lecture seule [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Renvoie :**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

Renvoie l'objet TableFormat qui contient les propriétés de mise en forme de ce tableau. Lecture seule [ITableFormat](../../com.aspose.slides/itableformat).

**Renvoie :**
[ITableFormat](../../com.aspose.slides/itableformat)

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Fusionne les cellules voisines.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Cellule à fusionner. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Cellule à fusionner. |
| allowSplitting | boolean | True pour autoriser la division des cellules. |

**Renvoie :**
[ICell](../../com.aspose.slides/icell) - Cellule fusionnée.

### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

Obtient ou définit le style de tableau intégré. Lecture/écriture [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Renvoie :**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

Obtient ou définit le style de tableau intégré. Lecture/écriture [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

Détermine si le tableau a un sens de lecture de droite à gauche. Lecture-écriture boolean.

**Renvoie :**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

Détermine si le tableau a un sens de lecture de droite à gauche. Lecture-écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

Détermine si la première ligne d'un tableau doit être dessinée avec une mise en forme spéciale. Lecture/écriture boolean.

**Renvoie :**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

Détermine si la première ligne d'un tableau doit être dessinée avec une mise en forme spéciale. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

Détermine si la première colonne d'un tableau doit être dessinée avec une mise en forme spéciale. Lecture/écriture boolean.

**Renvoie :**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

Détermine si la première colonne d'un tableau doit être dessinée avec une mise en forme spéciale. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

Détermine si la dernière ligne d'un tableau doit être dessinée avec une mise en forme spéciale. Lecture/écriture boolean.

**Renvoie :**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

Détermine si la dernière ligne d'un tableau doit être dessinée avec une mise en forme spéciale. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

Détermine si la dernière colonne d'un tableau doit être dessinée avec une mise en forme spéciale. Lecture/écriture boolean.

**Renvoie :**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

Détermine si la dernière colonne d'un tableau doit être dessinée avec une mise en forme spéciale. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

Détermine si les lignes paires doivent être dessinées avec une mise en forme différente. Lecture/écriture boolean.

**Renvoie :**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

Détermine si les lignes paires doivent être dessinées avec une mise en forme différente. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

Détermine si les colonnes paires doivent être dessinées avec une mise en forme différente. Lecture/écriture boolean.

**Renvoie :**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

Détermine si les colonnes paires doivent être dessinées avec une mise en forme différente. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Définit les propriétés de format de portion définies pour toutes les portions des cellules du tableau.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | Objet IPortionFormat avec les propriétés nécessaires définies. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Définit les propriétés de format de paragraphe définies pour tous les paragraphes des cellules du tableau.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | Objet IParagraphFormat avec les propriétés nécessaires définies. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Définit les propriétés de format de cadre de texte définies pour tous les cadres de texte des cellules du tableau.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | Objet ITextFrameFormat avec les propriétés nécessaires définies. |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Renvoie un objet TableFormat.FillFormat contenant le format de remplissage pour le tableau. Lecture seule [IFillFormat](../../com.aspose.slides/ifillformat).

**Renvoie :**
[IFillFormat](../../com.aspose.slides/ifillformat)