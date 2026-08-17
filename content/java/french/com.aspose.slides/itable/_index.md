---
title: ITable
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un tableau sur une diapositive.
type: docs
url: /fr/com.aspose.slides/itable/
---
**Toutes les interfaces implémentées :**  
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

Représente un tableau sur une diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Renvoie la cellule aux indices de colonne et de ligne spécifiés. |
| [getRows()](#getRows--) | Renvoie la collection de lignes. |
| [getColumns()](#getColumns--) | Renvoie la collection de colonnes. |
| [getTableFormat()](#getTableFormat--) | Renvoie l’objet TableFormat qui contient les propriétés de formatage de ce tableau. |
| [getStylePreset()](#getStylePreset--) | Obtient ou définit le style de tableau intégré. |
| [setStylePreset(int value)](#setStylePreset-int-) | Obtient ou définit le style de tableau intégré. |
| [getRightToLeft()](#getRightToLeft--) | Détermine si le tableau a un ordre de lecture de droite à gauche. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Détermine si le tableau a un ordre de lecture de droite à gauche. |
| [getFirstRow()](#getFirstRow--) | Détermine si la première ligne d’un tableau doit être dessinée avec un formatage spécial. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Détermine si la première ligne d’un tableau doit être dessinée avec un formatage spécial. |
| [getFirstCol()](#getFirstCol--) | Détermine si la première colonne d’un tableau doit être dessinée avec un formatage spécial. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Détermine si la première colonne d’un tableau doit être dessinée avec un formatage spécial. |
| [getLastRow()](#getLastRow--) | Détermine si la dernière ligne d’un tableau doit être dessinée avec un formatage spécial. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Détermine si la dernière ligne d’un tableau doit être dessinée avec un formatage spécial. |
| [getLastCol()](#getLastCol--) | Détermine si la dernière colonne d’un tableau doit être dessinée avec un formatage spécial. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Détermine si la dernière colonne d’un tableau doit être dessinée avec un formatage spécial. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Détermine si les lignes paires doivent être dessinées avec un formatage différent. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Détermine si les lignes paires doivent être dessinées avec un formatage différent. |
| [getVerticalBanding()](#getVerticalBanding--) | Détermine si les colonnes paires doivent être dessinées avec un formatage différent. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Détermine si les colonnes paires doivent être dessinées avec un formatage différent. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Fusionne les cellules voisines. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

Renvoie la cellule aux indices de colonne et de ligne spécifiés. Lecture seule [ICell](../../com.aspose.slides/icell).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Renvoie :**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

Renvoie la collection de lignes. Lecture seule [IRowCollection](../../com.aspose.slides/irowcollection).

**Renvoie :**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

Renvoie la collection de colonnes. Lecture seule [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Renvoie :**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

Renvoie l’objet TableFormat qui contient les propriétés de formatage de ce tableau. Lecture seule [ITableFormat](../../com.aspose.slides/itableformat).

**Renvoie :**
[ITableFormat](../../com.aspose.slides/itableformat)
### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

Obtient ou définit le style de tableau intégré. Lecture/écriture [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Renvoie :**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

Obtient ou définit le style de tableau intégré. Lecture/écriture [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Détermine si le tableau a un ordre de lecture de droite à gauche. Booléen lecture-écriture.

**Renvoie :**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

Détermine si le tableau a un ordre de lecture de droite à gauche. Booléen lecture-écriture.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

Détermine si la première ligne d’un tableau doit être dessinée avec un formatage spécial. Booléen lecture-écriture.

**Renvoie :**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

Détermine si la première ligne d’un tableau doit être dessinée avec un formatage spécial. Booléen lecture-écriture.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

Détermine si la première colonne d’un tableau doit être dessinée avec un formatage spécial. Booléen lecture-écriture.

**Renvoie :**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

Détermine si la première colonne d’un tableau doit être dessinée avec un formatage spécial. Booléen lecture-écriture.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

Détermine si la dernière ligne d’un tableau doit être dessinée avec un formatage spécial. Booléen lecture-écriture.

**Renvoie :**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

Détermine si la dernière ligne d’un tableau doit être dessinée avec un formatage spécial. Booléen lecture-écriture.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

Détermine si la dernière colonne d’un tableau doit être dessinée avec un formatage spécial. Booléen lecture-écriture.

**Renvoie :**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

Détermine si la dernière colonne d’un tableau doit être dessinée avec un formatage spécial. Booléen lecture-écriture.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

Détermine si les lignes paires doivent être dessinées avec un formatage différent. Booléen lecture-écriture.

**Renvoie :**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

Détermine si les lignes paires doivent être dessinées avec un formatage différent. Booléen lecture-écriture.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

Détermine si les colonnes paires doivent être dessinées avec un formatage différent. Booléen lecture-écriture.

**Renvoie :**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

Détermine si les colonnes paires doivent être dessinées avec un formatage différent. Booléen lecture-écriture.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Fusionne les cellules voisines.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Cellule à fusionner. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Cellule à fusionner. |
| allowSplitting | boolean | True pour autoriser le fractionnement des cellules. |

**Renvoie :**
[ICell](../../com.aspose.slides/icell) - Cellule fusionnée.