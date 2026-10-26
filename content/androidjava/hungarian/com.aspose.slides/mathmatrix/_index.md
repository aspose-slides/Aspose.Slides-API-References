---
title: MathMatrix
second_title: Aspose.Slides Androidhoz a Java API hivatkozás
description: Meghatározza a Matrix objektumot, amely gyermekelemekből áll, egy vagy több sorra és oszlopra elrendezve.
type: docs
url: /hu/com.aspose.slides/mathmatrix/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Minden megvalósított interfész:**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

Meghatározza a Matrix objektumot, amely olyan gyermekelemekből áll, amelyek egy vagy több sorba és oszlopba vannak rendezve. Fontos megjegyezni, hogy a mátrixoknak nincsenek beépített határolóik. A mátrixot a zárójelekbe helyezni a határolóobjektum (IMathDelimiter) használatával kell. Null argumentumok használhatók a mátrixokban hézagok létrehozásához.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | Inicializál egy új MathMatrix példányt. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getRowCount()](#getRowCount--) | Sorok száma a mátrixban |
| [getColumnCount()](#getColumnCount--) | Oszlopok száma a mátrixban |
| [getHidePlaceholders()](#getHidePlaceholders--) | Elrejti az üres mátrixelemek helyőrzőit Default: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Elrejti az üres mátrixelemek helyőrzőit Default: false |
| [getBaseJustification()](#getBaseJustification--) | Megadja a függőleges igazítást a környező szöveghez képest. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Megadja a függőleges igazítást a környező szöveghez képest. |
| [getMinColumnWidth()](#getMinColumnWidth--) | A minimális oszlopszélesség twipben (1/20 pont) A rést (amelyet \\u201cColumn Gap\\u201d vagy \\u201cGap Width\\u201d néven is ismernek) a MinColumnWidth-hez adják, hogy meghatározzák a teljes Matrix oszlopszakazást (a különböző oszlopok azonos élei közötti távolság). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | A minimális oszlopszélesség twipben (1/20 pont) A rést (amelyet \\u201cColumn Gap\\u201d vagy \\u201cGap Width\\u201d néven is ismernek) a MinColumnWidth-hez adják, hogy meghatározzák a teljes Matrix oszlopszakazást (a különböző oszlopok azonos élei közötti távolság). |
| [getColumnGapRule()](#getColumnGapRule--) | A vízszintes hézag típusa a mátrix oszlopai között; a vízszintes hézag egységei lehetnek em vagy pont (twipben tárolva). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | A vízszintes hézag típusa a mátrix oszlopai között; a vízszintes hézag egységei lehetnek em vagy pont (twipben tárolva). |
| [getColumnGap()](#getColumnGap--) | A vízszintes hézag értéke a mátrix oszlopai között; ha a ColumnGapRule 3-ra (\"Exactly\") van állítva, akkor az egységet twipként (1/20 pont) értelmezi; ha a ColumnGapRule 4-re (\"Multiple\") van állítva, akkor az egységet 0.5 em lépések számaként értelmezi. |
| [setColumnGap(long value)](#setColumnGap-long-) | A vízszintes hézag értéke a mátrix oszlopai között; ha a ColumnGapRule 3-ra (\"Exactly\") van állítva, akkor az egységet twipként (1/20 pont) értelmezi; ha a ColumnGapRule 4-re (\"Multiple\") van állítva, akkor az egységet 0.5 em lépések számaként értelmezi. |
| [getRowGapRule()](#getRowGapRule--) | A függőleges hézag típusa a mátrix sorai között; a függőleges hézag egységei lehetnek sorok vagy pontok (twipben tárolva). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | A függőleges hézag típusa a mátrix sorai között; a függőleges hézag egységei lehetnek sorok vagy pontok (twipben tárolva). |
| [getRowGap()](#getRowGap--) | A függőleges hézag értéke a mátrix sorai között; ha a RowGapRule 3-ra (\"Exactly\") van állítva, akkor az egységet twipként (1/20 pont) értelmezi; ha a RowGapRule 4-re (\"Multiple\") van állítva, akkor az egységet fél-sorokként értelmezi. |
| [setRowGap(long value)](#setRowGap-long-) | A függőleges hézag értéke a mátrix sorai között; ha a RowGapRule 3-ra (\"Exactly\") van állítva, akkor az egységet twipként (1/20 pont) értelmezi; ha a RowGapRule 4-re (\"Multiple\") van állítva, akkor az egységet fél-sorokként értelmezi. |
| [get_Item(int row, int column)](#get-Item-int-int-) | A mátrix eleme |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | A mátrix eleme |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vezérlőkarakter tulajdonságok |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Megkapja a megadott oszlop vízszintes igazítását |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Beállítja a megadott oszlop vízszintes igazítását |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Beállítja a megadott oszlopok vízszintes igazítását |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Beszúr egy új sort a megadott előtt. Kezdetben az új sor összes eleme null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Beszúr egy új sort a megadott után. Kezdetben az új sor összes eleme null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Törli a megadott sort. |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Beszúr egy új oszlopot a megadott előtt. Kezdetben az új oszlop összes eleme null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Beszúr egy új oszlopot a megadott után. Kezdetben az új oszlop összes eleme null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Törli a megadott oszlopot. |
| [getChildren()](#getChildren--) | Lekéri a gyermekelemeket |

### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

Inicializál egy új MathMatrix példányt.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rowCount | int | sorok száma |
| columnCount | int | oszlopok száma |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
```

Sorok száma a mátrixban

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
public final int getColumnCount()
```

Oszlopok száma a mátrixban

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
public final boolean getHidePlaceholders()
```

Elrejti az üres mátrixelemek helyőrzőit Default: false

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
public final void setHidePlaceholders(boolean value)
```

Elrejti az üres mátrixelemek helyőrzőit Default: false

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
public final int getBaseJustification()
```

Megadja a függőleges igazítást a környező szöveghez képest. Lehetséges értékek: top, bottom, és center. Alapértelmezett: Center

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
public final void setBaseJustification(int value)
```

Megadja a függőleges igazítást a környező szöveghez képest. Lehetséges értékek: top, bottom, és center. Alapértelmezett: Center

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
public final long getMinColumnWidth()
```

A minimális oszlopszélesség twipben (1/20 pont) A rést (amelyet \\u201cColumn Gap\\u201d vagy \\u201cGap Width\\u201d néven is ismernek) a MinColumnWidth-hez adják, hogy meghatározzák a teljes Matrix oszlopszakazást (a különböző oszlopok azonos élei közötti távolság). Alapértelmezett: 0.

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
public final void setMinColumnWidth(long value)
```

A minimális oszlopszélesség twipben (1/20 pont) A rést (amelyet \\u201cColumn Gap\\u201d vagy \\u201cGap Width\\u201d néven is ismernek) a MinColumnWidth-hez adják, hogy meghatározzák a teljes Matrix oszlopszakazást (a különböző oszlopok azonos élei közötti távolság). Alapértelmezett: 0.

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
public final int getColumnGapRule()
```

A vízszintes hézag típusa a mátrix oszlopai között; a vízszintes hézag egységei lehetnek em vagy pont (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)

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
public final void setColumnGapRule(int value)
```

A vízszintes hézag típusa a mátrix oszlopai között; a vízszintes hézag egységei lehetnek em vagy pont (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)

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
public final long getColumnGap()
```

A vízszintes hézag értéke a mátrix oszlopai között; ha a ColumnGapRule 3-ra (\"Exactly\") van állítva, akkor az egységet twipként (1/20 pont) értelmezi; ha a ColumnGapRule 4-re (\"Multiple\") van állítva, akkor az egységet 0.5 em lépések számaként értelmezi. Más esetekben figyelmen kívül hagyja. Alapértelmezett: 0

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
public final void setColumnGap(long value)
```

A vízszintes hézag értéke a mátrix oszlopai között; ha a ColumnGapRule 3-ra (\"Exactly\") van állítva, akkor az egységet twipként (1/20 pont) értelmezi; ha a ColumnGapRule 4-re (\"Multiple\") van állítva, akkor az egységet 0.5 em lépések számaként értelmezi. Más esetekben figyelmen kívül hagyja. Alapértelmezett: 0

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
public final int getRowGapRule()
```

A függőleges hézag típusa a mátrix sorai között; a függőleges hézag egységei lehetnek sorok vagy pontok (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)

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
public final void setRowGapRule(int value)
```

A függőleges hézag típusa a mátrix sorai között; a függőleges hézag egységei lehetnek sorok vagy pontok (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)

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
public final long getRowGap()
```

A függőleges hézag értéke a mátrix sorai között; ha a RowGapRule 3-ra (\"Exactly\") van állítva, akkor az egységet twipként (1/20 pont) értelmezi; ha a RowGapRule 4-re (\"Multiple\") van állítva, akkor az egységet fél-sorokként értelmezi. Alapértelmezett: 0

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
public final void setRowGap(long value)
```

A függőleges hézag értéke a mátrix sorai között; ha a RowGapRule 3-ra (\"Exactly\") van állítva, akkor az egységet twipként (1/20 pont) értelmezi; ha a RowGapRule 4-re (\"Multiple\") van állítva, akkor az egységet fél-sorokként értelmezi. Alapértelmezett: 0

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

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```

A mátrix eleme

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
| row | int | A sor null-alapú indexe, amelynek az eleme lekérendő |
| column | int | Az oszlop null-alapú indexe, amelynek az eleme lekérendő |

**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```

A mátrix eleme

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
| row | int | A sor null-alapú indexe, amelynek az eleme lekérendő |
| column | int | Az oszlop null-alapú indexe, amelynek az eleme lekérendő |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Vezérlőkarakter tulajdonságok

**Visszatérési érték:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```

Megkapja a megadott oszlop vízszintes igazítását

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
| columnIndex | int | Null-alapú oszlopindex |

**Visszatérési érték:**
int - A megadott oszlop vízszintes igazítása
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

Beállítja a megadott oszlop vízszintes igazítását

--------------------

> ```
> Példa:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| columnIndex | int | Null-alapú oszlopindex |
| val | int | A megadott oszlop vízszintes igazításának új értéke |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Beállítja a megadott oszlopok vízszintes igazítását

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
| columnIndex | int | Az első oszlop null-alapú indexe, amelynek az igazítása beállítandó |
| columnsCount | long | A beállítandó oszlopok száma |
| val | int | A megadott oszlop vízszintes igazításának új értéke |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

Beszúr egy új sort a megadott előtt. Kezdetben az új sor összes eleme null.

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
| rowIndex | int | A sor indexe, amely előtt új sort kell beszúrni |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

Beszúr egy új sort a megadott után. Kezdetben az új sor összes eleme null.

--------------------

> ```
> Példa:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rowIndex | int | A sor indexe, amely után új sort kell beszúrni |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```

Törli a megadott sort

--------------------

> ```
> Példa:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rowIndex | int | A sor null-alapú indexe, amelyet törölni kell. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

Beszúr egy új oszlopot a megadott előtt. Kezdetben az új oszlop összes eleme null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| columnIndex | int | A oszlop indexe, amely előtt új oszlopot kell beszúrni |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

Beszúr egy új oszlopot a megadott után. Kezdetben az új oszlop összes eleme null.

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
| columnIndex | int | A oszlop indexe, amely után új oszlopot kell beszúrni |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```

Törli a megadott oszlopot

--------------------

> ```
> Példa:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| columnIndex | int | A oszlop null-alapú indexe, amelyet törölni kell. |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Lekéri a gyermekelemeket

**Visszatérési érték:**
com.aspose.slides.IMathElement[]