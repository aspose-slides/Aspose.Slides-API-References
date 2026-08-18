---
title: MathMatrix
second_title: Aspose.Slides Java API Referencia
description: Meghatározza a mátrix objektumot, amely gyermekelemekből áll, egy vagy több sorban és oszlopban elrendezve.
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

Meghatározza a mátrix objektumot, amely gyermekelemekből áll, egy vagy több sorban és oszlopban elrendezve. Fontos megjegyezni, hogy a mátrixok nem rendelkeznek beépített határolókkal. A mátrix zárójelekbe helyezéséhez a delimiter objektumot (IMathDelimiter) kell használni. Null argumentumok használhatók a mátrixokban hézagok létrehozásához.

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
| [getRowCount()](#getRowCount--) | A mátrix sorainak száma |
| [getColumnCount()](#getColumnCount--) | A mátrix oszlopainak száma |
| [getHidePlaceholders()](#getHidePlaceholders--) | Elrejti az üres mátrixelemek helykitöltőit. Alapértelmezett: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Elrejti az üres mátrixelemek helykitöltőit. Alapértelmezett: false |
| [getBaseJustification()](#getBaseJustification--) | Megadja a függőleges igazítást a környező szöveghez képest. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Megadja a függőleges igazítást a környező szöveghez képest. |
| [getMinColumnWidth()](#getMinColumnWidth--) | A legkisebb oszlopszélesség twipben (1/20 pont). A hézag (más néven \"Column Gap\" vagy \"Gap Width\") hozzáadódik a MinColumnWidth-hez a teljes mátrix oszlopszakasz meghatározásához (a különböző oszlopok azonos széleinek távolsága). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | A legkisebb oszlopszélesség twipben (1/20 pont). A hézag (más néven \"Column Gap\" vagy \"Gap Width\") hozzáadódik a MinColumnWidth-hez a teljes mátrix oszlopszakasz meghatározásához (a különböző oszlopok azonos széleinek távolsága). |
| [getColumnGapRule()](#getColumnGapRule--) | A mátrix oszlopai közötti vízszintes távolság típusa; a vízszintes távolság egységei lehetnek em vagy pont (twipben tárolva). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | A mátrix oszlopai közötti vízszintes távolság típusa; a vízszintes távolság egységei lehetnek em vagy pont (twipben tárolva). |
| [getColumnGap()](#getColumnGap--) | A mátrix oszlopai közötti vízszintes távolság értéke; ha a ColumnGapRule 3-ra (\"Exactly\") van állítva, akkor az egység twipként (1/20 pont) értelmeződik, ha 4-re (\"Multiple\"), akkor 0,5 em növekmények számaként. |
| [setColumnGap(long value)](#setColumnGap-long-) | A mátrix oszlopai közötti vízszintes távolság értéke; ha a ColumnGapRule 3-ra (\"Exactly\") van állítva, akkor az egység twipként (1/20 pont) értelmeződik, ha 4-re (\"Multiple\"), akkor 0,5 em növekmények számaként. |
| [getRowGapRule()](#getRowGapRule--) | A mátrix sorai közötti függőleges távolság típusa; a függőleges távolság egységei lehetnek sorok vagy pontok (twipben tárolva). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | A mátrix sorai közötti függőleges távolság típusa; a függőleges távolság egységei lehetnek sorok vagy pontok (twipben tárolva). |
| [getRowGap()](#getRowGap--) | A mátrix sorai közötti függőleges távolság értéke; ha a RowGapRule 3-ra (\"Exactly\") van állítva, akkor az egység twip (1/20 pont), ha 4-re (\"Multiple\"), akkor fél-sorokként értelmeződik. |
| [setRowGap(long value)](#setRowGap-long-) | A mátrix sorai közötti függőleges távolság értéke; ha a RowGapRule 3-ra (\"Exactly\") van állítva, akkor az egység twip (1/20 pont), ha 4-re (\"Multiple\"), akkor fél-sorokként értelmeződik. |
| [get_Item(int row, int column)](#get-Item-int-int-) | A mátrix eleme |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | A mátrix eleme |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontroll karakter tulajdonságok |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | A megadott oszlop vízszintes igazításának lekérése |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | A megadott oszlop vízszintes igazításának beállítása |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | A megadott oszlopok vízszintes igazításának beállítása |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Új sor beszúrása a megadott sor elé. Kezdetben az új sor összes eleme null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Új sor beszúrása a megadott sor után. Kezdetben az új sor összes eleme null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | A megadott sor törlése |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Új oszlop beszúrása a megadott oszlop elé. Kezdetben az új oszlop összes eleme null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Új oszlop beszúrása a megadott oszlop után. Kezdetben az új oszlop összes eleme null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | A megadott oszlop törlése |
| [getChildren()](#getChildren--) | Gyermekelemek lekérése |
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
public final int getColumnCount()
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
public final boolean getHidePlaceholders()
```

Elrejti az üres mátrixelemek helykitöltőit. Alapértelmezett: false

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

Elrejti az üres mátrixelemek helykitöltőit. Alapértelmezett: false

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
public final void setBaseJustification(int value)
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
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public final long getMinColumnWidth()
```

A legkisebb oszlopszélesség twipben (1/20 pont). A hézag (más néven \"Column Gap\" vagy \"Gap Width\") hozzáadódik a MinColumnWidth-hez a teljes mátrix oszlopszakasz meghatározásához (a különböző oszlopok azonos széleinek távolsága). Alapértelmezett: 0.

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

A legkisebb oszlopszélesség twipben (1/20 pont). A hézag (más néven \"Column Gap\" vagy \"Gap Width\") hozzáadódik a MinColumnWidth-hez a teljes mátrix oszlopszakasz meghatározásához (a különböző oszlopok azonos széleinek távolsága). Alapértelmezett: 0.

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

A mátrix oszlopai közötti vízszintes távolság típusa; a vízszintes távolság egységei lehetnek em vagy pont (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)

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

A mátrix oszlopai közötti vízszintes távolság típusa; a vízszintes távolság egységei lehetnek em vagy pont (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)

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

A mátrix oszlopai közötti vízszintes távolság értéke; ha a ColumnGapRule 3-ra (\"Exactly\") van állítva, akkor az egység twipként (1/20 pont) értelmeződik, ha 4-re (\"Multiple\"), akkor 0,5 em növekmények számaként. Egyéb esetekben figyelmen kívül marad. Alapértelmezett: 0

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

A mátrix oszlopai közötti vízszintes távolság értéke; ha a ColumnGapRule 3-ra (\"Exactly\") van állítva, akkor az egység twipként (1/20 pont) értelmeződik, ha 4-re (\"Multiple\"), akkor 0,5 em növekmények számaként. Egyéb esetekben figyelmen kívül marad. Alapértelmezett: 0

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

A mátrix sorai közötti függőleges távolság típusa; a függőleges távolság egységei lehetnek sorok vagy pontok (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)

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

A mátrix sorai közötti függőleges távolság típusa; a függőleges távolság egységei lehetnek sorok vagy pontok (twipben tárolva). Alapértelmezett: SingleSpacingGap (0)

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

A mátrix sorai közötti függőleges távolság értéke; ha a RowGapRule 3-ra (\"Exactly\") van állítva, akkor az egység twip (1/20 pont), ha 4-re (\"Multiple\"), akkor fél-sorokként értelmeződik. Alapértelmezett: 0

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

A mátrix sorai közötti függőleges távolság értéke; ha a RowGapRule 3-ra (\"Exactly\") van állítva, akkor az egység twip (1/20 pont), ha 4-re (\"Multiple\"), akkor fél-sorokként értelmeződik. Alapértelmezett: 0

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
| row | int | A sor nulláról indexelt száma |
| column | int | Az oszlop nulláról indexelt száma |

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
| row | int | A sor nulláról indexelt száma |
| column | int | Az oszlop nulláról indexelt száma |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Kontroll karakter tulajdonságok

**Visszatérési érték:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
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
| columnIndex | int | Nulláról indexelt oszlopszám |

**Visszatérési érték:**
int - A megadott oszlop vízszintes igazítása
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
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
| columnIndex | int | Nulláról indexelt oszlopszám |
| val | int | Az új vízszintes igazítás értéke |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
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
| columnIndex | int | Az első oszlop nulláról indexelt száma, amelynek az igazítását be kell állítani |
| columnsCount | long | Az igazítandó oszlopok száma |
| val | int | Az új vízszintes igazítás értéke |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

Új sor beszúrása a megadott sor elé. Kezdetben az új sor összes eleme null.

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
| rowIndex | int | A sor indexe, amely elé új sort kell beszúrni |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

Új sor beszúrása a megadott sor után. Kezdetben az új sor összes eleme null.

--------------------

> ```
> Példa:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| rowIndex | int | A sor indexe, amely után új sort kell beszúrni |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```

A megadott sor törlése

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
| rowIndex | int | A sor nulláról indexelt száma, amelyet törölni kell. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

Új oszlop beszúrása a megadott oszlop elé. Kezdetben az új oszlop összes eleme null.

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
| columnIndex | int | A oszlop indexe, amely elé új oszlopot kell beszúrni |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

Új oszlop beszúrása a megadott oszlop után. Kezdetben az új oszlop összes eleme null.

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

A megadott oszlop törlése

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
| columnIndex | int | A oszlop nulláról indexelt száma, amelyet törölni kell. |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Gyermekelemek lekérése

**Visszatérési érték:**
com.aspose.slides.IMathElement[]