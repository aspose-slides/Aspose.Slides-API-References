---
title: IMathMatrix
second_title: Aspose.Slides pro Android přes referenci Java API
description: Specifikuje objekt Matrix, který se skládá z podřízených prvků uspořádaných v jednom nebo více řádcích a sloupcích.
type: docs
url: /cs/com.aspose.slides/imathmatrix/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Specifikuje objekt Matrix, který se skládá z podřízených prvků uspořádaných v jednom nebo více řádcích a sloupcích. Je důležité poznamenat, že matice nemají vestavěné ohraničení. Pro umístění matice do závorek byste měli použít objekt ohraničení (IMathDelimiter). Null argumenty lze použít k vytvoření mezer v maticích.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | Prvky matice |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Prvky matice |
| [getRowCount()](#getRowCount--) | Počet řádků v matici |
| [getColumnCount()](#getColumnCount--) | Počet sloupců v matici |
| [getHidePlaceholders()](#getHidePlaceholders--) | Skrýt zástupné znaky pro prázdné prvky matice. Výchozí: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Skrýt zástupné znaky pro prázdné prvky matice. Výchozí: false |
| [getBaseJustification()](#getBaseJustification--) | Určuje svislé zarovnání vzhledem k okolnímu textu. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Určuje svislé zarovnání vzhledem k okolnímu textu. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Minimální šířka sloupce v twips (1/20 bodu). Mezery (také označované jako \u201cColumn Gap\u201d nebo \u201cGap Width\u201d) jsou přičteny k MinColumnWidth pro určení celkového rozestupu sloupců v matici (vzdálenost mezi stejnými hranami různých sloupců). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Minimální šířka sloupce v twips (1/20 bodu). Mezery (také označované jako \u201cColumn Gap\u201d nebo \u201cGap Width\u201d) jsou přičteny k MinColumnWidth pro určení celkového rozestupu sloupců v matici (vzdálenost mezi stejnými hranami různých sloupců). |
| [getColumnGapRule()](#getColumnGapRule--) | Typ vodorovného rozestupu mezi sloupci matice; Jednotky rozestupu mohou být em nebo body (uloženy jako twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Typ vodorovného rozestupu mezi sloupci matice; Jednotky rozestupu mohou být em nebo body (uloženy jako twips). |
| [getColumnGap()](#getColumnGap--) | Hodnota vodorovného rozestupu mezi sloupci matice; Pokud je ColumnGapRule nastaven na 3 ("Exactly"), jednotka je interpretována jako twips (1/20 bodu). Pokud je ColumnGapRule nastaven na 4 ("Multiple"), jednotka je interpretována jako počet 0.5 em kroků. |
| [setColumnGap(long value)](#setColumnGap-long-) | Hodnota vodorovného rozestupu mezi sloupci matice; Pokud je ColumnGapRule nastaven na 3 ("Exactly"), jednotka je interpretována jako twips (1/20 bodu). Pokud je ColumnGapRule nastaven na 4 ("Multiple"), jednotka je interpretována jako počet 0.5 em kroků. |
| [getRowGapRule()](#getRowGapRule--) | Typ svislého rozestupu mezi řádky matice; Jednotky rozestupu mohou být řádky nebo body (uloženy jako twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Typ svislého rozestupu mezi řádky matice; Jednotky rozestupu mohou být řádky nebo body (uloženy jako twips). |
| [getRowGap()](#getRowGap--) | Hodnota svislého rozestupu mezi řádky matice; Pokud je RowGapRule nastaven na 3 ("Exactly"), jednotka je interpretována jako twips (1/20 bodu). Pokud je RowGapRule nastaven na 4 ("Multiple"), jednotka je interpretována jako půlřádky. |
| [setRowGap(long value)](#setRowGap-long-) | Hodnota svislého rozestupu mezi řádky matice; Pokud je RowGapRule nastaven na 3 ("Exactly"), jednotka je interpretována jako twips (1/20 bodu). Pokud je RowGapRule nastaven na 4 ("Multiple"), jednotka je interpretována jako půlřádky. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Získat vodorovné zarovnání určeného sloupce |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Nastavit vodorovné zarovnání určeného sloupce |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Nastavit vodorovné zarovnání určených sloupců |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Vložit nový řádek před zadaný. Původně jsou všechny prvky v novém řádku null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Vložit nový řádek za zadaný. Původně jsou všechny prvky v novém řádku null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Smaže zadaný řádek |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Vložit nový sloupec před zadaný. Původně jsou všechny prvky v novém sloupci null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Vložit nový sloupec za zadaný. Původně jsou všechny prvky v novém sloupci null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Smaže zadaný sloupec |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

Prvky matice

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| row | int | Nulový index řádku, pro získání položky |
| column | int | Nulový index sloupce, pro získání položky |

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement

### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```

Prvky matice

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| row | int | Nulový index řádku, pro nastavení položky |
| column | int | Nulový index sloupce, pro nastavení položky |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
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
public abstract int getColumnCount()
```

Počet sloupců v matici

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Vrací:**
int

### getHidePlaceholders() {#getHidePlaceholders--}
```
public abstract boolean getHidePlaceholders()
```

Skrýt zástupné znaky pro prázdné prvky matice. Výchozí: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Vrací:**
boolean

### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```

Skrýt zástupné znaky pro prázdné prvky matice. Výchozí: false

--------------------

> ```
> Example:
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
public abstract int getBaseJustification()
```

Určuje svislé zarovnání vzhledem k okolnímu textu. Možné hodnoty jsou top, bottom a center. Výchozí: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Vrací:**
int

### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Určuje svislé zarovnání vzhledem k okolnímu textu. Možné hodnoty jsou top, bottom a center. Výchozí: Center

--------------------

> ```
> Example:
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
public abstract long getMinColumnWidth()
```

Minimální šířka sloupce v twips (1/20 bodu). Mezery (také označované jako \u201cColumn Gap\u201d nebo \u201cGap Width\u201d) jsou přičteny k MinColumnWidth pro určení celkového rozestupu sloupců v matici (vzdálenost mezi stejnými hranami různých sloupců). Výchozí: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Vrací:**
long

### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```

Minimální šířka sloupce v twips (1/20 bodu). Mezery (také označované jako \u201cColumn Gap\u201d nebo \u201cGap Width\u201d) jsou přičteny k MinColumnWidth pro určení celkového rozestupu sloupců v matici (vzdálenost mezi stejnými hranami různých sloupců). Výchozí: 0.

--------------------

> ```
> Example:
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
public abstract int getColumnGapRule()
```

Typ vodorovného rozestupu mezi sloupci matice; Jednotky rozestupu mohou být em nebo body (uloženy jako twips). Výchozí: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Vrací:**
int

### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public abstract void setColumnGapRule(int value)
```

Typ vodorovného rozestupu mezi sloupci matice; Jednotky rozestupu mohou být em nebo body (uloženy jako twips). Výchozí: SingleSpacingGap (0)

--------------------

> ```
> Example:
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
public abstract long getColumnGap()
```

Hodnota vodorovného rozestupu mezi sloupci matice; Pokud je ColumnGapRule nastaven na 3 ("Exactly"), jednotka je interpretována jako twips (1/20 bodu). Pokud je ColumnGapRule nastaven na 4 ("Multiple"), jednotka je interpretována jako počet 0.5 em kroků. V ostatních případech je ignorována. Výchozí: 0

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
public abstract void setColumnGap(long value)
```

Hodnota vodorovného rozestupu mezi sloupci matice; Pokud je ColumnGapRule nastaven na 3 ("Exactly"), jednotka je interpretována jako twips (1/20 bodu). Pokud je ColumnGapRule nastaven na 4 ("Multiple"), jednotka je interpretována jako počet 0.5 em kroků. V ostatních případech je ignorována. Výchozí: 0

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
public abstract int getRowGapRule()
```

Typ svislého rozestupu mezi řádky matice; Jednotky rozestupu mohou být řádky nebo body (uloženy jako twips). Výchozí: SingleSpacingGap (0)

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
public abstract void setRowGapRule(int value)
```

Typ svislého rozestupu mezi řádky matice; Jednotky rozestupu mohou být řádky nebo body (uloženy jako twips). Výchozí: SingleSpacingGap (0)

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
public abstract long getRowGap()
```

Hodnota svislého rozestupu mezi řádky matice; Pokud je RowGapRule nastaven na 3 ("Exactly"), jednotka je interpretována jako twips (1/20 bodu). Pokud je RowGapRule nastaven na 4 ("Multiple"), jednotka je interpretována jako půlřádky. Výchozí: 0

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
public abstract void setRowGap(long value)
```

Hodnota svislého rozestupu mezi řádky matice; Pokud je RowGapRule nastaven na 3 ("Exactly"), jednotka je interpretována jako twips (1/20 bodu). Pokud je RowGapRule nastaven na 4 ("Multiple"), jednotka je interpretována jako půlřádky. Výchozí: 0

--------------------

> ```
> Příklad:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

Získat vodorovné zarovnání určeného sloupce

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | int | Index sloupce od nuly |

**Vrací:**
int - Vodorovné zarovnání určeného sloupce

### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

Nastavit vodorovné zarovnání určeného sloupce

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | int | Index sloupce od nuly |
| val | int | Nová hodnota vodorovného zarovnání určeného sloupce |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Nastavit vodorovné zarovnání určených sloupců

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
| columnIndex | int | Index prvního sloupce, jehož zarovnání má být nastaveno |
| columnsCount | long | Počet sloupců, pro které se má nastavit zarovnání |
| val | int | Nová hodnota vodorovného zarovnání určeného sloupce |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

Vložit nový řádek před zadaný. Původně jsou všechny prvky v novém řádku null.

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
| rowIndex | int | Index řádku, před který se má vložit nový řádek |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

Vložit nový řádek za zadaný. Původně jsou všechny prvky v novém řádku null.

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
| rowIndex | int | Index řádku, za který se má vložit nový řádek |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```

Smaže zadaný řádek

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| rowIndex | int | Nulový index řádku, který má být smazán. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

Vložit nový sloupec před zadaný. Původně jsou všechny prvky v novém sloupci null.

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
| columnIndex | int | Index sloupce, před který se má vložit nový sloupec |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

Vložit nový sloupec za zadaný. Původně jsou všechny prvky v novém sloupci null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | int | Index sloupce, za který se má vložit nový sloupec |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```

Smaže zadaný sloupec

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | int | Nulový index sloupce, který má být smazán. |