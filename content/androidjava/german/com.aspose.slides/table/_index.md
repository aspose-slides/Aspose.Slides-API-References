---
title: Table
second_title: Aspose.Slides für Android über die Java API-Referenz
description: Stellt eine Tabelle auf einer Folie dar.
type: docs
url: /de/com.aspose.slides/table/
---
**Vererbung:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Alle implementierten Schnittstellen:**  
[com.aspose.slides.ITable](../../com.aspose.slides/itable)  
```
public final class Table extends GraphicalObject implements ITable
```

Stellt eine Tabelle auf einer Folie dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Gibt die Zelle an den angegebenen Spalten- und Zeilenindizes zurück. |
| [getRows()](#getRows--) | Gibt die Sammlung der Zeilen zurück. |
| [getColumns()](#getColumns--) | Gibt die Sammlung der Spalten zurück. |
| [getTableFormat()](#getTableFormat--) | Gibt das TableFormat-Objekt zurück, das die Formatierungseigenschaften für diese Tabelle enthält. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Fügt benachbarte Zellen zusammen. |
| [getStylePreset()](#getStylePreset--) | Liest oder setzt integrierten Tabellestil. |
| [setStylePreset(int value)](#setStylePreset-int-) | Liest oder setzt integrierten Tabellestil. |
| [getRightToLeft()](#getRightToLeft--) | Ermittelt, ob die Tabelle von rechts nach links gelesen wird. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Ermittelt, ob die Tabelle von rechts nach links gelesen wird. |
| [getFirstRow()](#getFirstRow--) | Ermittelt, ob die erste Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Ermittelt, ob die erste Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [getFirstCol()](#getFirstCol--) | Ermittelt, ob die erste Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Ermittelt, ob die erste Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [getLastRow()](#getLastRow--) | Ermittelt, ob die letzte Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Ermittelt, ob die letzte Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [getLastCol()](#getLastCol--) | Ermittelt, ob die letzte Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Ermittelt, ob die letzte Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Ermittelt, ob die geraden Zeilen mit einer anderen Formatierung gezeichnet werden müssen. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Ermittelt, ob die geraden Zeilen mit einer anderen Formatierung gezeichnet werden müssen. |
| [getVerticalBanding()](#getVerticalBanding--) | Ermittelt, ob die geraden Spalten mit einer anderen Formatierung gezeichnet werden müssen. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Ermittelt, ob die geraden Spalten mit einer anderen Formatierung gezeichnet werden müssen. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Setzt definierte Portionenformat-Eigenschaften für alle Abschnitte der Tabellenzellen. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Setzt definierte Absatzformat-Eigenschaften für alle Absätze der Tabellenzellen. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Setzt definierte Textrahmenformat-Eigenschaften für alle Textrahmen der Tabellenzellen. |
| [getFillFormat()](#getFillFormat--) | Gibt ein TableFormat.FillFormat-Objekt zurück, das die Füllformatierung für die Tabelle enthält. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

Gibt die Zelle an den angegebenen Spalten- und Zeilenindizes zurück. Nur Lesezugriff [Cell](../../com.aspose.slides/cell).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Rückgabewert:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

Gibt die Sammlung der Zeilen zurück. Nur Lesezugriff [IRowCollection](../../com.aspose.slides/irowcollection).

**Rückgabewert:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

Gibt die Sammlung der Spalten zurück. Nur Lesezugriff [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Rückgabewert:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

Gibt das TableFormat-Objekt zurück, das die Formatierungseigenschaften für diese Tabelle enthält. Nur Lesezugriff [ITableFormat](../../com.aspose.slides/itableformat).

**Rückgabewert:**
[ITableFormat](../../com.aspose.slides/itableformat)

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Fügt benachbarte Zellen zusammen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Zu mergeende Zelle. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Zu mergeende Zelle. |
| allowSplitting | boolean | True, um das Aufteilen von Zellen zu erlauben. |

**Rückgabewert:**
[ICell](../../com.aspose.slides/icell) – Zusammengeführte Zelle.

### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

Liest oder setzt integrierten Tabellestil. Lesen/Schreiben [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Rückgabewert:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

Liest oder setzt integrierten Tabellestil. Lesen/Schreiben [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

Ermittelt, ob die Tabelle von rechts nach links gelesen wird. Lesen/Schreiben  boolean .

**Rückgabewert:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

Ermittelt, ob die Tabelle von rechts nach links gelesen wird. Lesen/Schreiben  boolean .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

Ermittelt, ob die erste Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben  boolean .

**Rückgabewert:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

Ermittelt, ob die erste Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben  boolean .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

Ermittelt, ob die erste Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben  boolean .

**Rückgabewert:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

Ermittelt, ob die erste Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben  boolean .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

Ermittelt, ob die letzte Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben  boolean .

**Rückgabewert:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

Ermittelt, ob die letzte Zeile einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben  boolean .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

Ermittelt, ob die letzte Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben  boolean .

**Rückgabewert:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

Ermittelt, ob die letzte Spalte einer Tabelle mit einer speziellen Formatierung gezeichnet werden muss. Lesen/Schreiben  boolean .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

Ermittelt, ob die geraden Zeilen mit einer anderen Formatierung gezeichnet werden müssen. Lesen/Schreiben  boolean .

**Rückgabewert:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

Ermittelt, ob die geraden Zeilen mit einer anderen Formatierung gezeichnet werden müssen. Lesen/Schreiben  boolean .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

Ermittelt, ob die geraden Spalten mit einer anderen Formatierung gezeichnet werden müssen. Lesen/Schreiben  boolean .

**Rückgabewert:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

Ermittelt, ob die geraden Spalten mit einer anderen Formatierung gezeichnet werden müssen. Lesen/Schreiben  boolean .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Setzt definierte Portionenformat-Eigenschaften für alle Abschnitte der Tabellenzellen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat-Objekt mit den erforderlichen Eigenschaften gesetzt. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Setzt definierte Absatzformat-Eigenschaften für alle Absätze der Tabellenzellen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat-Objekt mit den erforderlichen Eigenschaften gesetzt. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Setzt definierte Textrahmenformat-Eigenschaften für alle Textrahmen der Tabellenzellen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat-Objekt mit den erforderlichen Eigenschaften gesetzt. |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Gibt ein TableFormat.FillFormat-Objekt zurück, das die Füllformatierung für die Tabelle enthält. Nur Lesezugriff [IFillFormat](../../com.aspose.slides/ifillformat).

**Rückgabewert:**
[IFillFormat](../../com.aspose.slides/ifillformat)