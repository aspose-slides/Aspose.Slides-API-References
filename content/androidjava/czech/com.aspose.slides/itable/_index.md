---
title: ITable
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Představuje tabulku na snímku.
type: docs
url: /cs/com.aspose.slides/itable/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

Representuje tabulku na snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Vrací Cell na zadaných indexech sloupce a řádku. |
| [getRows()](#getRows--) | Vrací kolekci řádků. |
| [getColumns()](#getColumns--) | Vrací kolekci sloupců. |
| [getTableFormat()](#getTableFormat--) | Vrací objekt TableFormat, který obsahuje vlastnosti formátování pro tuto tabulku. |
| [getStylePreset()](#getStylePreset--) | Načítá nebo nastavuje vestavěný styl tabulky. |
| [setStylePreset(int value)](#setStylePreset-int-) | Načítá nebo nastavuje vestavěný styl tabulky. |
| [getRightToLeft()](#getRightToLeft--) | Určuje, zda má tabulka směr čtení zprava doleva. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Určuje, zda má tabulka směr čtení zprava doleva. |
| [getFirstRow()](#getFirstRow--) | Určuje, zda má být první řádek tabulky vykreslen se speciálním formátováním. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Určuje, zda má být první řádek tabulky vykreslen se speciálním formátováním. |
| [getFirstCol()](#getFirstCol--) | Určuje, zda má být první sloupec tabulky vykreslen se speciálním formátováním. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Určuje, zda má být první sloupec tabulky vykreslen se speciálním formátováním. |
| [getLastRow()](#getLastRow--) | Určuje, zda má být poslední řádek tabulky vykreslen se speciálním formátováním. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Určuje, zda má být poslední řádek tabulky vykreslen se speciálním formátováním. |
| [getLastCol()](#getLastCol--) | Určuje, zda má být poslední sloupec tabulky vykreslen se speciálním formátováním. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Určuje, zda má být poslední sloupec tabulky vykreslen se speciálním formátováním. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Určuje, zda mají být sudé řádky vykresleny s odlišným formátováním. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Určuje, zda mají být sudé řádky vykresleny s odlišným formátováním. |
| [getVerticalBanding()](#getVerticalBanding--) | Určuje, zda mají být sudé sloupce vykresleny s odlišným formátováním. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Určuje, zda mají být sudé sloupce vykresleny s odlišným formátováním. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Spojuje sousední Cell. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

Vrací Cell na zadaných indexech sloupce a řádku. Pouze pro čtení [ICell](../../com.aspose.slides/icell).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Vrací:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

Vrací kolekci řádků. Pouze pro čtení [IRowCollection](../../com.aspose.slides/irowcollection).

**Vrací:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

Vrací kolekci sloupců. Pouze pro čtení [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Vrací:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

Vrací objekt TableFormat, který obsahuje vlastnosti formátování pro tuto tabulku. Pouze pro čtení [ITableFormat](../../com.aspose.slides/itableformat).

**Vrací:**
[ITableFormat](../../com.aspose.slides/itableformat)
### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

Načítá nebo nastavuje vestavěný styl tabulky. Čtení/zápis [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Vrací:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

Načítá nebo nastavuje vestavěný styl tabulky. Čtení/zápis [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Určuje, zda má tabulka směr čtení zprava doleva. Čtení-zápis boolean.

**Vrací:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

Určuje, zda má tabulka směr čtení zprava doleva. Čtení-zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

Určuje, zda má být první řádek tabulky vykreslen se speciálním formátováním. Čtení/zápis boolean.

**Vrací:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

Určuje, zda má být první řádek tabulky vykreslen se speciálním formátováním. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

Určuje, zda má být první sloupec tabulky vykreslen se speciálním formátováním. Čtení/zápis boolean.

**Vrací:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

Určuje, zda má být první sloupec tabulky vykreslen se speciálním formátováním. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

Určuje, zda má být poslední řádek tabulky vykreslen se speciálním formátováním. Čtení/zápis boolean.

**Vrací:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

Určuje, zda má být poslední řádek tabulky vykreslen se speciálním formátováním. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

Určuje, zda má být poslední sloupec tabulky vykreslen se speciálním formátováním. Čtení/zápis boolean.

**Vrací:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

Určuje, zda má být poslední sloupec tabulky vykreslen se speciálním formátováním. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

Určuje, zda mají být sudé řádky vykresleny s odlišným formátováním. Čtení/zápis boolean.

**Vrací:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

Určuje, zda mají být sudé řádky vykresleny s odlišným formátováním. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

Určuje, zda mají být sudé sloupce vykresleny s odlišným formátováním. Čtení/zápis boolean.

**Vrací:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

Určuje, zda mají být sudé sloupce vykresleny s odlišným formátováním. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Spojuje sousední Cell.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Cell k sloučení. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Cell k sloučení. |
| allowSplitting | boolean | True pro povolení rozdělení Cell. |

**Vrací:**
[ICell](../../com.aspose.slides/icell) - Sloučený Cell.