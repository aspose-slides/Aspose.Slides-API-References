---
title: IMathMatrix
second_title: Aspose.Slides Androidra a Java API referenciája
description: Megadja a Matrix objektumot, amely gyermekelemekből áll, és egy vagy több sorra és oszlopra van elrendezve.
type: docs
url: /hu/com.aspose.slides/imathmatrix/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Megadja a Matrix objektumot, amely gyermekelemekből áll, és egy vagy több sorra és oszlopra van elrendezve. Fontos megjegyezni, hogy a mátrixoknak nincsenek beépített határolóik. A mátrixot a zárójelek közé helyezni a delimiter objektum (IMathDelimiter) segítségével kell. Null argumentumok használhatók a mátrixokban hiányok létrehozásához.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Módszerek

| Method | Description |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | A mátrix elemei |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | A mátrix elemei |
| [getRowCount()](#getRowCount--) | A mátrix sorainak száma |
| [getColumnCount()](#getColumnCount--) | A mátrix oszlopainak száma |
| [getHidePlaceholders()](#getHidePlaceholders--) | Az üres mátrixelemek helykitöltőinek elrejtése Alapértelmezett: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Az üres mátrixelemek helykitöltőinek elrejtése Alapértelmezett: false |
| [getBaseJustification()](#getBaseJustification--) | Megadja a függőleges igazítást a környező szöveghez képest. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Megadja a függőleges igazítást a környező szöveghez képest. |
| [getMinColumnWidth()](#getMinColumnWidth--) | A minimális oszlopszélesség twipben (1/20 pont). A hézag (úgy is "Column Gap" vagy "Gap Width" néven) hozzáadódik a MinColumnWidth-hez, hogy meghatározza a teljes mátrix oszloptávolságot (a különböző oszlopok ugyanazon élének távolsága). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | A minimális oszlopszélesség twipben (1/20 pont). A hézag (úgy is "Column Gap" vagy "Gap Width" néven) hozzáadódik a MinColumnWidth-hez, hogy meghatározza a teljes mátrix oszloptávolságot (a különböző oszlopok ugyanazon élének távolsága). |
| [getColumnGapRule()](#getColumnGapRule--) | Az oszlopok közötti vízszintes távolság típusa a mátrixban; a vízszintes távolság egységei lehetnek em vagy pont (twipben tárolva). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Az oszlopok közötti vízszintes távolság típusa a mátrixban; a vízszintes távolság egységei lehetnek em vagy pont (twipben tárolva). |
| [getColumnGap()](#getColumnGap--) | Az oszlopok közötti vízszintes távolság értéke a mátrixban; ha a ColumnGapRule értéke 3 („Exactly”), akkor az egység twipként (1/20 pont) értelmeződik, ha a ColumnGapRule értéke 4 („Multiple”), akkor az egységet 0,5 em lépések számaként értelmezzük. |
| [setColumnGap(long value)](#setColumnGap-long-) | Az oszlopok közötti vízszintes távolság értéke a mátrixban; ha a ColumnGapRule értéke 3 („Exactly”), akkor az egység twipként (1/20 pont) értelmeződik, ha a ColumnGapRule értéke 4 („Multiple”), akkor az egységet 0,5 em lépések számaként értelmezzük. |
| [getRowGapRule()](#getRowGapRule--) | A sorok közötti függőleges távolság típusa a mátrixban; a függőleges távolság egységei lehetnek sor vagy pont (twipben tárolva). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | A sorok közötti függőleges távolság típusa a mátrixban; a függőleges távolság egységei lehetnek sor vagy pont (twipben tárolva). |
| [getRowGap()](#getRowGap--) | A sorok közötti függőleges távolság értéke a mátrixban; ha a RowGapRule értéke 3 („Exactly”), akkor az egység twipként (1/20 pont) értelmeződik, ha a RowGapRule értéke 4 („Multiple”), akkor az egység félsorokként értelmeződik. |
| [setRowGap(long value)](#setRowGap-long-) | A sorok közötti függőleges távolság értéke a mátrixban; ha a RowGapRule értéke 3 („Exactly”), akkor az egység twipként (1/20 pont) értelmeződik, ha a RowGapRule értéke 4 („Multiple”), akkor az egység félsorokként értelmeződik. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | A megadott oszlop vízszintes igazításának lekérdezése |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | A megadott oszlop vízszintes igazításának beállítása |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | A megadott oszlopok vízszintes igazításának beállítása |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Új sor beszúrása a megadott sor elé. Alapértelmezés szerint az új sor összes eleme null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Új sor beszúrása a megadott sor után. Alapértelmezés szerint az új sor összes eleme null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | A megadott sor törlése |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Új oszlop beszúrása a megadott oszlop elé. Alapértelmezés szerint az új oszlop összes eleme null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Új oszlop beszúrása a megadott oszlop után. Alapértelmezés szerint az új oszlop összes eleme null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | A megadott oszlop törlése |

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
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | A nullaalapú indexe a sornak, amelynek az elemet kérjük le |
| column | int | A nullaalapú indexe az oszlopnak, amelynek az elemet kérjük le |

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
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | A nullaalapú indexe a sornak, amelynek az elemet kérjük le |
| column | int | A nullaalapú indexe az oszlopnak, amelynek az elemet kérjük le |
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

Az üres mátrixelemek helykitöltőinek elrejtése Alapértelmezett: false

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

Az üres mátrixelemek helykitöltőinek elrejtése Alapértelmezett: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

Megadja a függőleges igazítást a környező szöveghez képest. Lehetséges értékek: top, bottom, center. Alapértelmezett: Center

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

Megadja a függőleges igazítást a környező szöveghez képest. Lehetséges értékek: top, bottom, center. Alapértelmezett: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public abstract long getMinColumnWidth()
```

A minimális oszlopszélesség twipben (1/20 pont). A hézag (úgy is "Column Gap" vagy "Gap Width" néven) hozzáadódik a MinColumnWidth-hez, hogy meghatározza a teljes mátrix oszloptávolságot (a különböző oszlopok ugyanazon élének távolsága). Alapértelmezett: 0.

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

A minimális oszlopszélesség twipben (1/20 pont). A hézag (úgy is "Column Gap" vagy "Gap Width" néven) hozzáadódik a MinColumnWidth-hez, hogy meghatározza a teljes mátrix oszloptávolságot (a különböző oszlopok ugyanazon élének távolsága). Alapértelmezett: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public abstract int getColumnGapRule()
```

Az oszlopok közötti vízszintes távolság típusa a mátrixban; a vízszintes távolság egységei lehetnek em vagy pont (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)

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

Az oszlopok közötti vízszintes távolság típusa a mátrixban; a vízszintes távolság egységei lehetnek em vagy pont (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public abstract long getColumnGap()
```

Az oszlopok közötti vízszintes távolság értéke a mátrixban; ha a ColumnGapRule értéke 3 („Exactly”), akkor az egység twipként (1/20 pont) értelmeződik, ha a ColumnGapRule értéke 4 („Multiple”), akkor az egységet 0,5 em lépések számaként értelmezzük. Más esetekben figyelmen kívül marad. Alapértelmezett: 0

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

Az oszlopok közötti vízszintes távolság értéke a mátrixban; ha a ColumnGapRule értéke 3 („Exactly”), akkor az egység twipként (1/20 pont) értelmeződik, ha a ColumnGapRule értéke 4 („Multiple”), akkor az egységet 0,5 em lépések számaként értelmezzük. Más esetekben figyelmen kívül marad. Alapértelmezett: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public abstract int getRowGapRule()
```

A sorok közötti függőleges távolság típusa a mátrixban; a függőleges távolság egységei lehetnek sor vagy pont (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)

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

A sorok közötti függőleges távolság típusa a mátrixban; a függőleges távolság egységei lehetnek sor vagy pont (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public abstract long getRowGap()
```

A sorok közötti függőleges távolság értéke a mátrixban; ha a RowGapRule értéke 3 („Exactly”), akkor az egység twipként (1/20 pont) értelmeződik, ha a RowGapRule értéke 4 („Multiple”), akkor az egység félsorokként értelmeződik. Alapértelmezett: 0

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

A sorok közötti függőleges távolság értéke a mátrixban; ha a RowGapRule értéke 3 („Exactly”), akkor az egység twipként (1/20 pont) értelmeződik, ha a RowGapRule értéke 4 („Multiple”), akkor az egység félsorokként értelmeződik. Alapértelmezett: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

A megadott oszlop vízszintes igazításának lekérdezése

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Paraméterek:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
> Példa:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```


**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Zero-based index of the first column to set alignment |
| columnsCount | long | The number of columns to specify the alignment |
| val | int | New value of horizontal alignment of specified column |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

Új sor beszúrása a megadott sor elé. Alapértelmezés szerint az új sor összes eleme null.

--------------------

> ```
> Példa:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | Index of the row before which to insert a new one |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

Új sor beszúrása a megadott sor után. Alapértelmezés szerint az új sor összes eleme null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | Index of the row after which to insert a new one |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```

A megadott sor törlése

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | A nullaalapú indexe a sornak, amelyet törölni kíván. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

Új oszlop beszúrása a megadott oszlop elé. Alapértelmezés szerint az új oszlop összes eleme null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index of the column before which to insert a new one |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

Új oszlop beszúrása a megadott oszlop után. Alapértelmezés szerint az új oszlop összes eleme null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index of the column after which to insert a new one |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```

A megadott oszlop törlése

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | A nullaalapú indexe az oszlopnak, amelyet törölni kíván. |