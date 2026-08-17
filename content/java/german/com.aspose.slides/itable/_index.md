---
title: ITable
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Tabelle auf einer Folie dar.
type: docs
url: /de/com.aspose.slides/itable/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

Stellt eine Tabelle auf einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Gibt die Zelle an den angegebenen Spalten- und Zeilenindizes zurück. |
| [getRows()](#getRows--) | Gibt die Sammlung von Zeilen zurück. |
| [getColumns()](#getColumns--) | Gibt die Sammlung von Spalten zurück. |
| [getTableFormat()](#getTableFormat--) | Gibt das TableFormat-Objekt zurück, das Formatierungseigenschaften für diese Tabelle enthält. |
| [getStylePreset()](#getStylePreset--) | Liest oder setzt den integrierten Tabellenstil. |
| [setStylePreset(int value)](#setStylePreset-int-) | Liest oder setzt den integrierten Tabellenstil. |
| [getRightToLeft()](#getRightToLeft--) | Bestimmt, ob die Tabelle rechts-nach-links-Lesereihenfolge hat. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Bestimmt, ob die Tabelle rechts-nach-links-Lesereihenfolge hat. |
| [getFirstRow()](#getFirstRow--) | Bestimmt, ob die erste Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Bestimmt, ob die erste Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [getFirstCol()](#getFirstCol--) | Bestimmt, ob die erste Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Bestimmt, ob die erste Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [getLastRow()](#getLastRow--) | Bestimmt, ob die letzte Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Bestimmt, ob die letzte Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [getLastCol()](#getLastCol--) | Bestimmt, ob die letzte Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Bestimmt, ob die letzte Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Bestimmt, ob die geraden Zeilen mit einer anderen Formatierung gezeichnet werden müssen. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Bestimmt, ob die geraden Zeilen mit einer anderen Formatierung gezeichnet werden müssen. |
| [getVerticalBanding()](#getVerticalBanding--) | Bestimmt, ob die geraden Spalten mit einer anderen Formatierung gezeichnet werden müssen. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Bestimmt, ob die geraden Spalten mit einer anderen Formatierung gezeichnet werden müssen. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Fügt benachbarte Zellen zusammen. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

Gibt die Zelle an den angegebenen Spalten- und Zeilenindizes zurück. Nur-Lesen [ICell](../../com.aspose.slides/icell).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Rückgabe:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

Gibt die Sammlung von Zeilen zurück. Nur-Lesen [IRowCollection](../../com.aspose.slides/irowcollection).

**Rückgabe:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

Gibt die Sammlung von Spalten zurück. Nur-Lesen [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Rückgabe:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

Gibt das TableFormat-Objekt zurück, das Formatierungseigenschaften für diese Tabelle enthält. Nur-Lesen [ITableFormat](../../com.aspose.slides/itableformat).

**Rückgabe:**
[ITableFormat](../../com.aspose.slides/itableformat)

### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

Liest oder setzt den integrierten Tabellenstil. Lesen/Schreiben [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Rückgabe:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

Liest oder setzt den integrierten Tabellenstil. Lesen/Schreiben [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Bestimmt, ob die Tabelle rechts-nach-links-Lesereihenfolge hat. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

Bestimmt, ob die Tabelle rechts-nach-links-Lesereihenfolge hat. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

Bestimmt, ob die erste Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

Bestimmt, ob die erste Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

Bestimmt, ob die erste Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

Bestimmt, ob die erste Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

Bestimmt, ob die letzte Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

Bestimmt, ob die letzte Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

Bestimmt, ob die letzte Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

Bestimmt, ob die letzte Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

Bestimmt, ob die geraden Zeilen mit einer anderen Formatierung gezeichnet werden müssen. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

Bestimmt, ob die geraden Zeilen mit einer anderen Formatierung gezeichnet werden müssen. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

Bestimmt, ob die geraden Spalten mit einer anderen Formatierung gezeichnet werden müssen. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

Bestimmt, ob die geraden Spalten mit einer anderen Formatierung gezeichnet werden müssen. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Fügt benachbarte Zellen zusammen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Cell zum Zusammenführen. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Cell zum Zusammenführen. |
| allowSplitting | boolean | True, um das Aufteilen von Zellen zu erlauben. |

**Rückgabe:**
[ICell](../../com.aspose.slides/icell) - Zusammengeführte Zelle.