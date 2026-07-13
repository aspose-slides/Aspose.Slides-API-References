---
title: ITable
second_title: Aspose.Slides voor Android via Java API-referentie
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
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Geeft de cel terug op de opgegeven kolom- en rij-indexen. |
| [getRows()](#getRows--) | Geeft de collectie van rijen terug. |
| [getColumns()](#getColumns--) | Geeft de collectie van kolommen terug. |
| [getTableFormat()](#getTableFormat--) | Geeft het TableFormat-object terug dat opmaak-eigenschappen voor deze tabel bevat. |
| [getStylePreset()](#getStylePreset--) | Stelt de ingebouwde tabelstijl in of haalt deze op. |
| [setStylePreset(int value)](#setStylePreset-int-) | Stelt de ingebouwde tabelstijl in of haalt deze op. |
| [getRightToLeft()](#getRightToLeft--) | Bepaalt of de tabel van rechts naar links gelezen moet worden. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Bepaalt of de tabel van rechts naar links gelezen moet worden. |
| [getFirstRow()](#getFirstRow--) | Bepaalt of de eerste rij van een tabel met een speciale opmaak getekend moet worden. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Bepaalt of de eerste rij van een tabel met een speciale opmaak getekend moet worden. |
| [getFirstCol()](#getFirstCol--) | Bepaalt of de eerste kolom van een tabel met een speciale opmaak getekend moet worden. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Bepaalt of de eerste kolom van een tabel met een speciale opmaak getekend moet worden. |
| [getLastRow()](#getLastRow--) | Bepaalt of de laatste rij van een tabel met een speciale opmaak getekend moet worden. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Bepaalt of de laatste rij van een tabel met een speciale opmaak getekend moet worden. |
| [getLastCol()](#getLastCol--) | Bepaalt of de laatste kolom van een tabel met een speciale opmaak getekend moet worden. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Bepaalt of de laatste kolom van een tabel met een speciale opmaak getekend moet worden. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Bepaalt of de even rijen met een andere opmaak getekend moeten worden. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Bepaalt of de even rijen met een andere opmaak getekend moeten worden. |
| [getVerticalBanding()](#getVerticalBanding--) | Bepaalt of de even kolommen met een andere opmaak getekend moeten worden. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Bepaalt of de even kolommen met een andere opmaak getekend moeten worden. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Voegt aangrenzende cellen samen. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

Geeft de cel terug op de opgegeven kolom- en rij-indexen. Alleen-lezen [ICell](../../com.aspose.slides/icell).

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

Geeft de collectie van rijen terug. Alleen-lezen [IRowCollection](../../com.aspose.slides/irowcollection).

**Retourneert:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

Geeft de collectie van kolommen terug. Alleen-lezen [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Retourneert:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

Geeft het TableFormat-object terug dat opmaak-eigenschappen voor deze tabel bevat. Alleen-lezen [ITableFormat](../../com.aspose.slides/itableformat).

**Retourneert:**
[ITableFormat](../../com.aspose.slides/itableformat)

### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

Stelt de ingebouwde tabelstijl in of haalt deze op. Lezen/schrijven [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Retourneert:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

Stelt de ingebouwde tabelstijl in of haalt deze op. Lezen/schrijven [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Bepaalt of de tabel van rechts naar links gelezen moet worden. Lezen-schrijven boolean.

**Retourneert:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

Bepaalt of de tabel van rechts naar links gelezen moet worden. Lezen-schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

Bepaalt of de eerste rij van een tabel met een speciale opmaak getekend moet worden. Lezen/schrijven boolean.

**Retourneert:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

Bepaalt of de eerste rij van een tabel met een speciale opmaak getekend moet worden. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

Bepaalt of de eerste kolom van een tabel met een speciale opmaak getekend moet worden. Lezen/schrijven boolean.

**Retourneert:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

Bepaalt of de eerste kolom van een tabel met een speciale opmaak getekend moet worden. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

Bepaalt of de laatste rij van een tabel met een speciale opmaak getekend moet worden. Lezen/schrijven boolean.

**Retourneert:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

Bepaalt of de laatste rij van een tabel met een speciale opmaak getekend moet worden. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

Bepaalt of de laatste kolom van een tabel met een speciale opmaak getekend moet worden. Lezen/schrijven boolean.

**Retourneert:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

Bepaalt of de laatste kolom van een tabel met een speciale opmaak getekend moet worden. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

Bepaalt of de even rijen met een andere opmaak getekend moeten worden. Lezen/schrijven boolean.

**Retourneert:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

Bepaalt of de even rijen met een andere opmaak getekend moeten worden. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

Bepaalt of de even kolommen met een andere opmaak getekend moeten worden. Lezen/schrijven boolean.

**Retourneert:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

Bepaalt of de even kolommen met een andere opmaak getekend moeten worden. Lezen/schrijven boolean.

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
| cell1 | [ICell](../../com.aspose.slides/icell) | Cel om te fuseren. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Cel om te fuseren. |
| allowSplitting | boolean | Waar om het splitsen van cellen toe te staan. |

**Retourneert:**
[ICell](../../com.aspose.slides/icell) - Samengevoegde cel.