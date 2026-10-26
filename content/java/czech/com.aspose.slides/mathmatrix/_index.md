---
title: MathMatrix
second_title: Aspose.Slides pro Java – reference API
description: Určuje objekt Matrix, který se skládá z podřízených prvků uspořádaných v jedné nebo více řadách a sloupcích.
type: docs
url: /cs/com.aspose.slides/mathmatrix/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Všechny implementované rozhraní:**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

Specifikuje objekt Matrix, který se skládá z podřízených prvků uspořádaných v jedné nebo více řadách a sloupcích. Je důležité poznamenat, že matice nemají vestavěné ohraničovače. Pro umístění matice do závorek byste měli použít objekt ohraničovače (IMathDelimiter). Null argumenty lze použít k vytvoření mezer v maticích.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | Inicializuje novou instanci třídy MathMatrix. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getRowCount()](#getRowCount--) | Počet řádků v matici |
| [getColumnCount()](#getColumnCount--) | Počet sloupců v matici |
| [getHidePlaceholders()](#getHidePlaceholders--) | Skryje zástupné znaky pro prázdné elementy matice Výchozí: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Skryje zástupné znaky pro prázdné elementy matice Výchozí: false |
| [getBaseJustification()](#getBaseJustification--) | Specifikuje vertikální zarovnání vzhledem k okolnímu textu. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Specifikuje vertikální zarovnání vzhledem k okolnímu textu. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Minimální šířka sloupce v twips (1/20 bodu) Rozteč mezery (také označována jako \\u201cColumn Gap\\u201d nebo \\u201cGap Width\\u201d) se přičte k MinColumnWidth pro určení celkové mezery sloupců matice (vzdálenost mezi stejnými okraji různých sloupců). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Minimální šířka sloupce v twips (1/20 bodu) Rozteč mezery (také označována jako \\u201cColumn Gap\\u201d nebo \\u201cGap Width\\u201d) se přičte k MinColumnWidth pro určení celkové mezery sloupců matice (vzdálenost mezi stejnými okraji různých sloupců). |
| [getColumnGapRule()](#getColumnGapRule--) | Typ horizontální mezery mezi sloupci matice; Jednotky horizontální mezery mohou být ems nebo body (uloženy jako twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Typ horizontální mezery mezi sloupci matice; Jednotky horizontální mezery mohou být ems nebo body (uloženy jako twips). |
| [getColumnGap()](#getColumnGap--) | Hodnota horizontální mezery mezi sloupci matice; Pokud je ColumnGapRule nastaven na 3 („Exactly“), jednotka je interpretována jako twips (1/20 bodu). Pokud je ColumnGapRule nastaven na 4 („Multiple“), jednotka je interpretována jako počet 0,5 em inkrementů. |
| [setColumnGap(long value)](#setColumnGap-long-) | Hodnota horizontální mezery mezi sloupci matice; Pokud je ColumnGapRule nastaven na 3 („Exactly“), jednotka je interpretována jako twips (1/20 bodu). Pokud je ColumnGapRule nastaven na 4 („Multiple“), jednotka je interpretována jako počet 0,5 em inkrementů. |
| [getRowGapRule()](#getRowGapRule--) | Typ vertikální mezery mezi řádky matice; Jednotky vertikální mezery mohou být řádky nebo body (uloženy jako twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Typ vertikální mezery mezi řádky matice; Jednotky vertikální mezery mohou být řádky nebo body (uloženy jako twips). |
| [getRowGap()](#getRowGap--) | Hodnota vertikální mezery mezi řádky matice; Pokud je RowGapRule nastaven na 3 („Exactly“), jednotka je interpretována jako twips (1/20 bodu). Pokud je RowGapRule nastaven na 4 („Multiple“), jednotka je interpretována jako půl-řádky. |
| [setRowGap(long value)](#setRowGap-long-) | Hodnota vertikální mezery mezi řádky matice; Pokud je RowGapRule nastaven na 3 („Exactly“), jednotka je interpretována jako twips (1/20 bodu). Pokud je RowGapRule nastaven na 4 („Multiple“), jednotka je interpretována jako půl-řádky. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Element matice |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Element matice |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vlastnosti ovládacích znaků |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Získá horizontální zarovnání zadaného sloupce |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Nastaví horizontální zarovnání zadaného sloupce |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Nastaví horizontální zarovnání zadaných sloupců |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Vloží nový řádek před zadaný. Počátečně jsou všechny elementy nového řádku null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Vloží nový řádek po zadaném. Počátečně jsou všechny elementy nového řádku null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Odstraní zadaný řádek |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Vloží nový sloupec před zadaný. Počátečně jsou všechny elementy nového sloupce null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Vloží nový sloupec po zadaném. Počátečně jsou všechny elementy nového sloupce null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Odstraní zadaný sloupec |
| [getChildren()](#getChildren--) | Získá podřízené elementy |
### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```


Inicializuje novou instanci třídy MathMatrix.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| rowCount | int | počet řádků |
| columnCount | int | počet sloupců |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
```


Počet řádků v matici

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Vrací:**
int
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```


Počet sloupců v matici

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Vrací:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public final boolean getHidePlaceholders()
```


Skryje zástupné znaky pro prázdné elementy matice Výchozí: false

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Vrací:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public final void setHidePlaceholders(boolean value)
```


Skryje zástupné znaky pro prázdné elementy matice Výchozí: false

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```


Specifikuje vertikální zarovnání vzhledem k okolnímu textu. Možné hodnoty jsou top, bottom a center. Výchozí: Center

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Vrací:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```


Specifikuje vertikální zarovnání vzhledem k okolnímu textu. Možné hodnoty jsou top, bottom a center. Výchozí: Center

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public final long getMinColumnWidth()
```


Minimální šířka sloupce v twips (1/20 bodu) Rozteč mezery (také označována jako \\u201cColumn Gap\\u201d nebo \\u201cGap Width\\u201d) se přičte k MinColumnWidth pro určení celkové mezery sloupců matice (vzdálenost mezi stejnými okraji různých sloupců). Výchozí: 0.

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Vrací:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public final void setMinColumnWidth(long value)
```


Minimální šířka sloupce v twips (1/20 bodu) Rozteč mezery (také označována jako \\u201cColumn Gap\\u201d nebo \\u201cGap Width\\u201d) se přičte k MinColumnWidth pro určení celkové mezery sloupců matice (vzdálenost mezi stejnými okraji různých sloupců). Výchozí: 0.

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public final int getColumnGapRule()
```


Typ horizontální mezery mezi sloupci matice; Jednotky horizontální mezery mohou být ems nebo body (uloženy jako twips). Výchozí: SingleSpacingGap (0)

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Vrací:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public final void setColumnGapRule(int value)
```


Typ horizontální mezery mezi sloupci matice; Jednotky horizontální mezery mohou být ems nebo body (uloženy jako twips). Výchozí: SingleSpacingGap (0)

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public final long getColumnGap()
```


Hodnota horizontální mezery mezi sloupci matice; Pokud je ColumnGapRule nastaven na 3 („Exactly“), jednotka je interpretována jako twips (1/20 bodu). Pokud je ColumnGapRule nastaven na 4 („Multiple“), jednotka je interpretována jako počet 0,5 em inkrementů. V ostatních případech ignorováno. Výchozí: 0

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Vrací:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public final void setColumnGap(long value)
```


Hodnota horizontální mezery mezi sloupci matice; Pokud je ColumnGapRule nastaven na 3 („Exactly“), jednotka je interpretována jako twips (1/20 bodu). Pokud je ColumnGapRule nastaven na 4 („Multiple“), jednotka je interpretována jako počet 0,5 em inkrementů. V ostatních případech ignorováno. Výchozí: 0

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public final int getRowGapRule()
```


Typ vertikální mezery mezi řádky matice; Jednotky vertikální mezery mohou být řádky nebo body (uloženy jako twips). Výchozí: SingleSpacingGap (0)

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Vrací:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public final void setRowGapRule(int value)
```


Typ vertikální mezery mezi řádky matice; Jednotky vertikální mezery mohou být řádky nebo body (uloženy jako twips). Výchozí: SingleSpacingGap (0)

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public final long getRowGap()
```


Hodnota vertikální mezery mezi řádky matice; Pokud je RowGapRule nastaven na 3 („Exactly“), jednotka je interpretována jako twips (1/20 bodu). Pokud je RowGapRule nastaven na 4 („Multiple“), jednotka je interpretována jako půl-řádky. Výchozí: 0

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Vrací:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public final void setRowGap(long value)
```


Hodnota vertikální mezery mezi řádky matice; Pokud je RowGapRule nastaven na 3 („Exactly“), jednotka je interpretována jako twips (1/20 bodu). Pokud je RowGapRule nastaven na 4 („Multiple“), jednotka je interpretována jako půl-řádky. Výchozí: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```


Element matice

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| row | int | Index řádku (od nuly) pro získání položky |
| column | int | Index sloupce (od nuly) pro získání položky |

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```


Element matice

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| row | int | Index řádku (od nuly) pro získání položky |
| column | int | Index sloupce (od nuly) pro získání položky |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Vlastnosti ovládacích znaků

**Vrací:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```


Získá horizontální zarovnání zadaného sloupce

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | int | Index sloupce (od nuly) |

**Vrací:**
int - Horizontální zarovnání zadaného sloupce
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```


Nastaví horizontální zarovnání zadaného sloupce

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | int | Index sloupce (od nuly) |
| val | int | Nová hodnota horizontálního zarovnání zadaného sloupce |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```


Nastaví horizontální zarovnání zadaných sloupců

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | int | Index první sloupce, pro který se nastavuje zarovnání |
| columnsCount | long | Počet sloupců, pro které se stanoví zarovnání |
| val | int | Nová hodnota horizontálního zarovnání zadaného sloupce |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```


Vloží nový řádek před zadaný. Počátečně jsou všechny elementy nového řádku null.

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| rowIndex | int | Index řádku, před který se vloží nový |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```


Vloží nový řádek po zadaném. Počátečně jsou všechny elementy nového řádku null.

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| rowIndex | int | Index řádku, po kterém se vloží nový |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```


Odstraní zadaný řádek

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| rowIndex | int | Index řádku (od nuly), který se má odstranit. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```


Vloží nový sloupec před zadaný. Počátečně jsou všechny elementy nového sloupce null.

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | int | Index sloupce, před který se vloží nový |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```


Vloží nový sloupec po zadaném. Počátečně jsou všechny elementy nového sloupce null.

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | int | Index sloupce, po kterém se vloží nový |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```


Odstraní zadaný sloupec

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | int | Index sloupce (od nuly), který se má odstranit. |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Získá podřízené elementy

**Vrací:**
com.aspose.slides.IMathElement[]