---
title: ITable
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une table sur une diapositive.
type: docs
url: /fr/com.aspose.slides/itable/
---
**Toutes les interfaces implémentées:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

Represente une table sur une diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Renvoie la cellule aux index de colonne et de ligne spécifiés. |
| [getRows()](#getRows--) | Renvoie la collection de lignes. |
| [getColumns()](#getColumns--) | Renvoie la collection de colonnes. |
| [getTableFormat()](#getTableFormat--) | Renvoie l'objet TableFormat qui contient les propriétés de mise en forme pour cette table. |
| [getStylePreset()](#getStylePreset--) | Obtient ou définit le style de table intégré. |
| [setStylePreset(int value)](#setStylePreset-int-) | Obtient ou définit le style de table intégré. |
| [getRightToLeft()](#getRightToLeft--) | Détermine si la table a un ordre de lecture de droite à gauche. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Détermine si la table a un ordre de lecture de droite à gauche. |
| [getFirstRow()](#getFirstRow--) | Détermine si la première ligne d'une table doit être dessinée avec un formatage spécial. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Détermine si la première ligne d'une table doit être dessinée avec un formatage spécial. |
| [getFirstCol()](#getFirstCol--) | Détermine si la première colonne d'une table doit être dessinée avec un formatage spécial. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Détermine si la première colonne d'une table doit être dessinée avec un formatage spécial. |
| [getLastRow()](#getLastRow--) | Détermine si la dernière ligne d'une table doit être dessinée avec un formatage spécial. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Détermine si la dernière ligne d'une table doit être dessinée avec un formatage spécial. |
| [getLastCol()](#getLastCol--) | Détermine si la dernière colonne d'une table doit être dessinée avec un formatage spécial. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Détermine si la dernière colonne d'une table doit être dessinée avec un formatage spécial. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Détermine si les lignes paires doivent être dessinées avec un formatage différent. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Détermine si les lignes paires doivent être dessinées avec un formatage différent. |
| [getVerticalBanding()](#getVerticalBanding--) | Détermine si les colonnes paires doivent être dessinées avec un formatage différent. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Détermine si les colonnes paires doivent être dessinées avec un formatage différent. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Fusionne les cellules adjacentes. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

Renvoie la cellule aux index de colonne et de ligne spécifiés. Lecture seule [ICell](../../com.aspose.slides/icell).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Retour:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

Renvoie la collection de lignes. Lecture seule [IRowCollection](../../com.aspose.slides/irowcollection).

**Retour:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

Renvoie la collection de colonnes. Lecture seule [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Retour:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

Renvoie l'objet TableFormat qui contient les propriétés de mise en forme pour cette table. Lecture seule [ITableFormat](../../com.aspose.slides/itableformat).

**Retour:**
[ITableFormat](../../com.aspose.slides/itableformat)
### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

Obtient ou définit le style de table intégré. Lecture/écriture [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Retour:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

Obtient ou définit le style de table intégré. Lecture/écriture [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Détermine si la table a un ordre de lecture de droite à gauche. Lecture/écriture booléen.

**Retour:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

Détermine si la table a un ordre de lecture de droite à gauche. Lecture/écriture booléen.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

Détermine si la première ligne d'une table doit être dessinée avec un formatage spécial. Lecture/écriture booléen.

**Retour:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

Détermine si la première ligne d'une table doit être dessinée avec un formatage spécial. Lecture/écriture booléen.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

Détermine si la première colonne d'une table doit être dessinée avec un formatage spécial. Lecture/écriture booléen.

**Retour:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

Détermine si la première colonne d'une table doit être dessinée avec un formatage spécial. Lecture/écriture booléen.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

Détermine si la dernière ligne d'une table doit être dessinée avec un formatage spécial. Lecture/écriture booléen.

**Retour:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

Détermine si la dernière ligne d'une table doit être dessinée avec un formatage spécial. Lecture/écriture booléen.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

Détermine si la dernière colonne d'une table doit être dessinée avec un formatage spécial. Lecture/écriture booléen.

**Retour:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

Détermine si la dernière colonne d'une table doit être dessinée avec un formatage spécial. Lecture/écriture booléen.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

Détermine si les lignes paires doivent être dessinées avec un formatage différent. Lecture/écriture booléen.

**Retour:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

Détermine si les lignes paires doivent être dessinées avec un formatage différent. Lecture/écriture booléen.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

Détermine si les colonnes paires doivent être dessinées avec un formatage différent. Lecture/écriture booléen.

**Retour:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

Détermine si les colonnes paires doivent être dessinées avec un formatage différent. Lecture/écriture booléen.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Fusionne les cellules adjacentes.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Cell to merge. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Cell to merge. |
| allowSplitting | boolean | True to allow cells splitting. |

**Retour:**
[ICell](../../com.aspose.slides/icell) - Merged cell.