---
title: ITable
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een tabel op een dia voor.
type: docs
url: /nl/com.aspose.slides/itable/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

Stelt een tabel op een dia voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Retourneert de cel op de opgegeven kolom- en rij-indexen. |
| [getRows()](#getRows--) | Retourneert de verzameling rijen. |
| [getColumns()](#getColumns--) | Retourneert de verzameling kolommen. |
| [getTableFormat()](#getTableFormat--) | Retourneert het TableFormat-object dat opmaak-eigenschappen voor deze tabel bevat. |
| [getStylePreset()](#getStylePreset--) | Haalt of stelt de ingebouwde tabelstijl in. |
| [setStylePreset(int value)](#setStylePreset-int-) | Haalt of stelt de ingebouwde tabelstijl in. |
| [getRightToLeft()](#getRightToLeft--) | Bepaalt of de tabel een rechts-naar-links-leesvolgorde heeft. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Bepaalt of de tabel een rechts-naar-links-leesvolgorde heeft. |
| [getFirstRow()](#getFirstRow--) | Bepaalt of de eerste rij van een tabel moet worden getekend met een speciale opmaak. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Bepaalt of de eerste rij van een tabel moet worden getekend met een speciale opmaak. |
| [getFirstCol()](#getFirstCol--) | Bepaalt of de eerste kolom van een tabel moet worden getekend met een speciale opmaak. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Bepaalt of de eerste kolom van een tabel moet worden getekend met een speciale opmaak. |
| [getLastRow()](#getLastRow--) | Bepaalt of de laatste rij van een tabel moet worden getekend met een speciale opmaak. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Bepaalt of de laatste rij van een tabel moet worden getekend met een speciale opmaak. |
| [getLastCol()](#getLastCol--) | Bepaalt of de laatste kolom van een tabel moet worden getekend met een speciale opmaak. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Bepaalt of de laatste kolom van een tabel moet worden getekend met een speciale opmaak. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Bepaalt of de even rijen moeten worden getekend met een andere opmaak. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Bepaalt of de even rijen moeten worden getekend met een andere opmaak. |
| [getVerticalBanding()](#getVerticalBanding--) | Bepaalt of de even kolommen moeten worden getekend met een andere opmaak. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Bepaalt of de even kolommen moeten worden getekend met een andere opmaak. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Voegt aangrenzende cellen samen. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```


Retourneert de cel op de opgegeven kolom- en rij-indexen. Alleen-lezen [ICell](../../com.aspose.slides/icell).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Retourneert:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```


Retourneert de verzameling rijen. Alleen-lezen [IRowCollection](../../com.aspose.slides/irowcollection).

**Retourneert:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```


Retourneert de verzameling kolommen. Alleen-lezen [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Retourneert:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```


Retourneert het TableFormat-object dat opmaak-eigenschappen voor deze tabel bevat. Alleen-lezen [ITableFormat](../../com.aspose.slides/itableformat).

**Retourneert:**
[ITableFormat](../../com.aspose.slides/itableformat)
### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```


Haalt of stelt de ingebouwde tabelstijl in. Lezen/schrijven [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Retourneert:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```


Haalt of stelt de ingebouwde tabelstijl in. Lezen/schrijven [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```


Bepaalt of de tabel een rechts-naar-links-leesvolgorde heeft. Lezen-schrijven boolean.

**Retourneert:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```


Bepaalt of de tabel een rechts-naar-links-leesvolgorde heeft. Lezen-schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```


Bepaalt of de eerste rij van een tabel moet worden getekend met een speciale opmaak. Lezen-schrijven boolean.

**Retourneert:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```


Bepaalt of de eerste rij van een tabel moet worden getekend met een speciale opmaak. Lezen-schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```


Bepaalt of de eerste kolom van een tabel moet worden getekend met een speciale opmaak. Lezen-schrijven boolean.

**Retourneert:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```


Bepaalt of de eerste kolom van een tabel moet worden getekend met een speciale opmaak. Lezen-schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```


Bepaalt of de laatste rij van een tabel moet worden getekend met een speciale opmaak. Lezen-schrijven boolean.

**Retourneert:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```


Bepaalt of de laatste rij van een tabel moet worden getekend met een speciale opmaak. Lezen-schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```


Bepaalt of de laatste kolom van een tabel moet worden getekend met een speciale opmaak. Lezen-schrijven boolean.

**Retourneert:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```


Bepaalt of de laatste kolom van een tabel moet worden getekend met een speciale opmaak. Lezen-schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```


Bepaalt of de even rijen moeten worden getekend met een andere opmaak. Lezen-schrijven boolean.

**Retourneert:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```


Bepaalt of de even rijen moeten worden getekend met een andere opmaak. Lezen-schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```


Bepaalt of de even kolommen moeten worden getekend met een andere opmaak. Lezen-schrijven boolean.

**Retourneert:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```


Bepaalt of de even kolommen moeten worden getekend met een andere opmaak. Lezen-schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```


Voegt aangrenzende cellen samen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Cel om samen te voegen. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Cel om samen te voegen. |
| allowSplitting | boolean | Waar om het splitsen van cellen toe te staan. |

**Returns:**
[ICell](../../com.aspose.slides/icell) - Samengevoegde cel.