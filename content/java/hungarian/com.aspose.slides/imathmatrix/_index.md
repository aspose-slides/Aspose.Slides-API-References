---
title: IMathMatrix
second_title: Aspose.Slides for Java API Referencia
description: Megadja a Matrix objektumot, amely gyermekelemekből áll, amelyek egy vagy több sorban és oszlopban vannak elrendezve.
type: docs
url: /hu/com.aspose.slides/imathmatrix/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Megadja a Matrix objektumot, amely gyermekelemeket tartalmaz, amelyek egy vagy több sorban és oszlopban vannak elrendezve. Fontos megjegyezni, hogy a mátrixoknak nincs beépített határolójele. A mátrix zárójelek közé helyezéséhez a határoló objektumot (IMathDelimiter) kell használni. Null argumentumok használhatók a mátrixokban hézagok létrehozásához.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | Elements of matrix |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Elements of matrix |
| [getRowCount()](#getRowCount--) | Number of rows in the matrix |
| [getColumnCount()](#getColumnCount--) | Number of columns in the matrix |
| [getHidePlaceholders()](#getHidePlaceholders--) | Hide the placeholders for empty matrix elements Default: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Hide the placeholders for empty matrix elements Default: false |
| [getBaseJustification()](#getBaseJustification--) | Specifies the vertical justification respect to surrounding text. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Specifies the vertical justification respect to surrounding text. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). |
| [getColumnGapRule()](#getColumnGapRule--) | The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). |
| [getColumnGap()](#getColumnGap--) | The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. |
| [setColumnGap(long value)](#setColumnGap-long-) | The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. |
| [getRowGapRule()](#getRowGapRule--) | The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). |
| [getRowGap()](#getRowGap--) | The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. |
| [setRowGap(long value)](#setRowGap-long-) | The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Get the horizontal alignment of the specified column |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Set the horizontal alignment of the specified column |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Set the horizontal alignment of the specified columns |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Insert a new row before the specified one Initially all elements in the new row are null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Insert a new row after the specified one Initially all elements in the new row are null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Deletes the specified row |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Insert a new column before the specified one Initially all elements in the new column are null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Insert a new column after the specified one Initially all elements in the new column are null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Deletes the specified column |
### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

A mátrix elemei

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |

**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```

A mátrix elemei

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
```

A mátrix sorainak száma

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Visszatérési érték:**
int
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

A mátrix oszlopainak száma

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Visszatérési érték:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public abstract boolean getHidePlaceholders()
```

Elrejti az üres mátrix elemek helyőrzőit Default: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Visszatérési érték:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```

Elrejti az üres mátrix elemek helyőrzőit Default: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

Megadja a függőleges igazítást a környező szöveghez viszonyítva. Lehetséges értékek: top, bottom, center. Alapértelmezett: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```


**Visszatérési érték:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Megadja a függőleges igazítást a környező szöveghez viszonyítva. Lehetséges értékek: top, bottom, center. Alapértelmezett: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public abstract long getMinColumnWidth()
```

Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). Default: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Visszatérési érték:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```

Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). Default: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public abstract int getColumnGapRule()
```

A mátrix oszlopai közötti vízszintes távolság típusa; a vízszintes távolság mértékegysége lehet em vagy pont (twipsban tárolva). Alapértelmezett: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Visszatérési érték:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public abstract void setColumnGapRule(int value)
```

A mátrix oszlopai közötti vízszintes távolság típusa; a vízszintes távolság mértékegysége lehet em vagy pont (twipsban tárolva). Alapértelmezett: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public abstract long getColumnGap()
```

A mátrix oszlopai közötti vízszintes távolság értéke; ha a ColumnGapRule értéke 3 ("Exactly"), akkor az egység twips (1/20 pont) alapján értelmeződik. Ha a ColumnGapRule értéke 4 ("Multiple"), akkor az egység 0,5 em lépés száma szerint értelmeződik. Egyéb esetekben figyelmen kívül hagyott. Alapértelmezett: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Visszatérési érték:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public abstract void setColumnGap(long value)
```

A mátrix oszlopai közötti vízszintes távolság értéke; ha a ColumnGapRule értéke 3 ("Exactly"), akkor az egység twips (1/20 pont) alapján értelmeződik. Ha a ColumnGapRule értéke 4 ("Multiple"), akkor az egység 0,5 em lépés száma szerint értelmeződik. Egyéb esetekben figyelmen kívül hagyott. Alapértelmezett: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public abstract int getRowGapRule()
```

A mátrix sorai közötti függőleges távolság típusa; a függőleges távolság mértékegysége lehet sor vagy pont (twipsban tárolva). Alapértelmezett: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Visszatérési érték:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```

A mátrix sorai közötti függőleges távolság típusa; a függőleges távolság mértékegysége lehet sor vagy pont (twipsban tárolva). Alapértelmezett: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public abstract long getRowGap()
```

A mátrix sorai közötti függőleges távolság értéke; ha a RowGapRule értéke 3 ("Exactly"), akkor az egység twips (1/20 pont) alapján értelmeződik. Ha a RowGapRule értéke 4 ("Multiple"), akkor az egység fél sor szerint értelmeződik. Alapértelmezett: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Visszatérési érték:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public abstract void setRowGap(long value)
```

A mátrix sorai közötti függőleges távolság értéke; ha a RowGapRule értéke 3 ("Exactly"), akkor az egység twips (1/20 pont) alapján értelmeződik. Ha a RowGapRule értéke 4 ("Multiple"), akkor az egység fél sor szerint értelmeződik. Alapértelmezett: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

A megadott oszlop vízszintes igazításának lekérése

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| columnIndex | int | Zero-based column index |

**Visszatérési érték:**
int - Horizontal Alignment of specified column
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

A megadott oszlop vízszintes igazításának beállítása

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| columnIndex | int | Zero-based column index |
| val | int | New value of horizontal alignment of specified column |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

A megadott oszlopok vízszintes igazításának beállítása

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| columnIndex | int | Zero-based index of the first column to set alignment |
| columnsCount | long | The number of columns to specify the alignment |
| val | int | New value of horizontal alignment of specified column |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

Új sort szúr be a megadott sor előtt. Kezdetben az új sor összes eleme null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rowIndex | int | Index of the row before which to insert a new one |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

Új sort szúr be a megadott sor után. Kezdetben az új sor összes eleme null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rowIndex | int | Index of the row after which to insert a new one |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```

Törli a megadott sort

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rowIndex | int | The zero-based index of the row to delete. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

Új oszlopot szúr be a megadott oszlop előtt. Kezdetben az új oszlop összes eleme null.

--------------------

> ```
public abstract void insertColumnBefore(int columnIndex)
```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| columnIndex | int | Index of the column before which to insert a new one |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

Új oszlopot szúr be a megadott oszlop után. Kezdetben az új oszlop összes eleme null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| columnIndex | int | Index of the column after which to insert a new one |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```

Törli a megadott oszlopot

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| columnIndex | int | The zero-based index of the column to delete. |