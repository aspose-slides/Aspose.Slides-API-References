---
title: Table
second_title: Aspose.Slides für Java API Referenz
description: Stellt eine Tabelle auf einer Folie dar.
type: docs
url: /de/com.aspose.slides/table/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**
[com.aspose.slides.ITable](../../com.aspose.slides/itable)
```
public final class Table extends GraphicalObject implements ITable
```

Stellt eine Tabelle auf einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Gibt die Zelle an den angegebenen Spalten- und Zeilenindizes zurück. |
| [getRows()](#getRows--) | Gibt die Sammlung von Zeilen zurück. |
| [getColumns()](#getColumns--) | Gibt die Sammlung von Spalten zurück. |
| [getTableFormat()](#getTableFormat--) | Gibt das TableFormat-Objekt zurück, das die Formatierungseigenschaften für diese Tabelle enthält. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Fügt benachbarte Zellen zusammen. |
| [getStylePreset()](#getStylePreset--) | Ruft den integrierten Tabellestil ab oder legt ihn fest. |
| [setStylePreset(int value)](#setStylePreset-int-) | Ruft den integrierten Tabellestil ab oder legt ihn fest. |
| [getRightToLeft()](#getRightToLeft--) | Bestimmt, ob die Tabelle von rechts nach links gelesen wird. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Bestimmt, ob die Tabelle von rechts nach links gelesen wird. |
| [getFirstRow()](#getFirstRow--) | Bestimmt, ob die erste Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Bestimmt, ob die erste Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [getFirstCol()](#getFirstCol--) | Bestimmt, ob die erste Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Bestimmt, ob die erste Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [getLastRow()](#getLastRow--) | Bestimmt, ob die letzte Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Bestimmt, ob die letzte Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [getLastCol()](#getLastCol--) | Bestimmt, ob die letzte Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Bestimmt, ob die letzte Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Bestimmt, ob gerade Zeilen mit einer anderen Formatierung gezeichnet werden müssen. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Bestimmt, ob gerade Zeilen mit einer anderen Formatierung gezeichnet werden müssen. |
| [getVerticalBanding()](#getVerticalBanding--) | Bestimmt, ob gerade Spalten mit einer anderen Formatierung gezeichnet werden müssen. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Bestimmt, ob gerade Spalten mit einer anderen Formatierung gezeichnet werden müssen. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Legt definierte Portion-Format-Eigenschaften für alle Zellportionen fest. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Legt definierte Absatzformat-Eigenschaften für alle Tabellenzellenabsätze fest. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Legt definierte Textrahmen-Format-Eigenschaften für alle Textrahmen der Tabellenzellen fest. |
| [getFillFormat()](#getFillFormat--) | Gibt ein TableFormat.FillFormat-Objekt zurück, das die Füllformatierung für die Tabelle enthält. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

Gibt die Zelle an den angegebenen Spalten- und Zeilenindizes zurück. Nur lesbar [Cell](../../com.aspose.slides/cell).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Rückgabe:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

Gibt die Sammlung von Zeilen zurück. Nur lesbar [IRowCollection](../../com.aspose.slides/irowcollection).

**Rückgabe:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

Gibt die Sammlung von Spalten zurück. Nur lesbar [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Rückgabe:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

Gibt das TableFormat-Objekt zurück, das die Formatierungseigenschaften für diese Tabelle enthält. Nur lesbar [ITableFormat](../../com.aspose.slides/itableformat).

**Rückgabe:**
[ITableFormat](../../com.aspose.slides/itableformat)

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Fügt benachbarte Zellen zusammen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Zelle zum Zusammenführen. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Zelle zum Zusammenführen. |
| allowSplitting | boolean | True, um das Teilen von Zellen zu erlauben. |

**Rückgabe:**
[ICell](../../com.aspose.slides/icell) - Zusammengeführte Zelle.

### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

Ruft den integrierten Tabellestil ab oder legt ihn fest. Lesen/Schreiben [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Rückgabe:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

Ruft den integrierten Tabellestil ab oder legt ihn fest. Lesen/Schreiben [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

Bestimmt, ob die Tabelle von rechts nach links gelesen wird. Lesen/Schreiben boolean .

**Rückgabe:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

Bestimmt, ob die Tabelle von rechts nach links gelesen wird. Lesen/Schreiben boolean .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

Bestimmt, ob die erste Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben boolean .

**Rückgabe:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

Bestimmt, ob die erste Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben boolean .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

Bestimmt, ob die erste Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben boolean .

**Rückgabe:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

Bestimmt, ob die erste Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben boolean .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

Bestimmt, ob die letzte Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben boolean .

**Rückgabe:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

Bestimmt, ob die letzte Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben boolean .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

Bestimmt, ob die letzte Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben boolean .

**Rückgabe:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

Bestimmt, ob die letzte Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben boolean .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

Bestimmt, ob gerade Zeilen mit einer anderen Formatierung gezeichnet werden müssen. Lesen/Schreiben boolean .

**Rückgabe:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

Bestimmt, ob gerade Zeilen mit einer anderen Formatierung gezeichnet werden müssen. Lesen/Schreiben boolean .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

Bestimmt, ob gerade Spalten mit einer anderen Formatierung gezeichnet werden müssen. Lesen/Schreiben boolean .

**Rückgabe:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

Bestimmt, ob gerade Spalten mit einer anderen Formatierung gezeichnet werden müssen. Lesen/Schreiben boolean .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Legt definierte Portion-Format-Eigenschaften für alle Zellportionen fest.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat-Objekt mit den notwendigen Eigenschaften. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Legt definierte Absatzformat-Eigenschaften für alle Tabellenzellenabsätze fest.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat-Objekt mit den notwendigen Eigenschaften. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Legt definierte Textrahmen-Format-Eigenschaften für alle Textrahmen der Tabellenzellen fest.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat-Objekt mit den notwendigen Eigenschaften. |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Gibt ein TableFormat.FillFormat-Objekt zurück, das die Füllformatierung für die Tabelle enthält. Nur lesbar [IFillFormat](../../com.aspose.slides/ifillformat).

**Rückgabe:**
[IFillFormat](../../com.aspose.slides/ifillformat)