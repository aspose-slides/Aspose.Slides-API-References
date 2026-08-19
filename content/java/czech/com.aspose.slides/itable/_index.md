---
title: ITable
second_title: Aspose.Slides pro Java API Reference
description: Představuje tabulku na snímku.
type: docs
url: /cs/com.aspose.slides/itable/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

Reprezentuje tabulku na snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Vrací buňku na zadaných indexech sloupce a řádku. |
| [getRows()](#getRows--) | Vrací kolekci řádků. |
| [getColumns()](#getColumns--) | Vrací kolekci sloupců. |
| [getTableFormat()](#getTableFormat--) | Vrací objekt TableFormat, který obsahuje vlastnosti formátování pro tuto tabulku. |
| [getStylePreset()](#getStylePreset--) | Získá nebo nastaví vestavěný styl tabulky. |
| [setStylePreset(int value)](#setStylePreset-int-) | Získá nebo nastaví vestavěný styl tabulky. |
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
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Spojí sousední buňky. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```


Vrací buňku na zadaných indexech sloupce a řádku. Pouze pro čtení [ICell](../../com.aspose.slides/icell).

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


Získá nebo nastaví vestavěný styl tabulky. Čtení/Zápis [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Vrací:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```


Získá nebo nastaví vestavěný styl tabulky. Čtení/Zápis [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```


Určuje, zda má tabulka směr čtení zprava doleva. Čtení/Zápis boolean.

**Vrací:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```


Určuje, zda má tabulka směr čtení zprava doleva. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```


Určuje, zda má být první řádek tabulky vykreslen se speciálním formátováním. Čtení/Zápis boolean.

**Vrací:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```


Určuje, zda má být první řádek tabulky vykreslen se speciálním formátováním. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```


Určuje, zda má být první sloupec tabulky vykreslen se speciálním formátováním. Čtení/Zápis boolean.

**Vrací:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```


Určuje, zda má být první sloupec tabulky vykreslen se speciálním formátováním. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```


Určuje, zda má být poslední řádek tabulky vykreslen se speciálním formátováním. Čtení/Zápis boolean.

**Vrací:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```


Určuje, zda má být poslední řádek tabulky vykreslen se speciálním formátováním. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```


Určuje, zda má být poslední sloupec tabulky vykreslen se speciálním formátováním. Čtení/Zápis boolean.

**Vrací:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```


Určuje, zda má být poslední sloupec tabulky vykreslen se speciálním formátováním. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```


Určuje, zda mají být sudé řádky vykresleny s odlišným formátováním. Čtení/Zápis boolean.

**Vrací:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```


Určuje, zda mají být sudé řádky vykresleny s odlišným formátováním. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```


Určuje, zda mají být sudé sloupce vykresleny s odlišným formátováním. Čtení/Zápis boolean.

**Vrací:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```


Určuje, zda mají být sudé sloupce vykresleny s odlišným formátováním. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```


Spojí sousední buňky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Buňka ke sloučení. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Buňka ke sloučení. |
| allowSplitting | boolean | Pravda, pokud má být povoleno rozdělení buněk. |

**Vrací:**
[ICell](../../com.aspose.slides/icell) - Sloučená buňka.