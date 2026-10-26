---
title: MathMatrix
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Specifikuje objekt Matrix, který se skládá z podřízených prvků uspořádaných v jednom nebo více řádcích a sloupcích.
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

Určuje objekt Matrix, který se skládá z podřízených prvků uspořádaných v jednom nebo více řádcích a sloupcích. Je důležité poznamenat, že matice nemají vestavěné oddělovače. Pro umístění matice do závorek byste měli použít objekt oddělovače (IMathDelimiter). Null argumenty mohou být použity k vytvoření mezer v matricích.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Konstruktoři

| Konstruktor | Popis |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | Inicializuje novou instanci třídy MathMatrix. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getRowCount()](#getRowCount--) | Počet řádků v matici |
| [getColumnCount()](#getColumnCount--) | Počet sloupců v matici |
| [getHidePlaceholders()](#getHidePlaceholders--) | Skryje zástupné symboly pro prázdné prvky matice Výchozí: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Skryje zástupné symboly pro prázdné prvky matice Výchozí: false |
| [getBaseJustification()](#getBaseJustification--) | Určuje svislé zarovnání vzhledem k okolnímu textu. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Určuje svislé zarovnání vzhledem k okolnímu textu. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Minimální šířka sloupce v twips (1/20 bodu). Rozestup mezery (také nazývaný „Column Gap“ nebo „Gap Width“) se přičítá k MinColumnWidth pro určení celkového rozestupu sloupců matice (vzdálenost mezi stejnými okraji různých sloupců). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Minimální šířka sloupce v twips (1/20 bodu). Rozestup mezery (také nazývaný „Column Gap“ nebo „Gap Width“) se přičítá k MinColumnWidth pro určení celkového rozestupu sloupců matice (vzdálenost mezi stejnými okraji různých sloupců). |
| [getColumnGapRule()](#getColumnGapRule--) | Typ vodorovného rozestupu mezi sloupci matice; jednotky vodorovného rozestupu mohou být ems nebo body (uložené jako twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Typ vodorovného rozestupu mezi sloupci matice; jednotky vodorovného rozestupu mohou být ems nebo body (uložené jako twips). |
| [getColumnGap()](#getColumnGap--) | Hodnota vodorovného rozestupu mezi sloupci matice; pokud je ColumnGapRule nastaveno na 3 („Exactly“), jednotka se interpretuje jako twips (1/20 bodu). Pokud je ColumnGapRule nastaveno na 4 („Multiple“), jednotka se interpretuje jako počet 0,5 em kroků. |
| [setColumnGap(long value)](#setColumnGap-long-) | Hodnota vodorovného rozestupu mezi sloupci matice; pokud je ColumnGapRule nastaveno na 3 („Exactly“), jednotka se interpretuje jako twips (1/20 bodu). Pokud je ColumnGapRule nastaveno na 4 („Multiple“), jednotka se interpretuje jako počet 0,5 em kroků. |
| [getRowGapRule()](#getRowGapRule--) | Typ svislého rozestupu mezi řádky matice; jednotky svislého rozestupu mohou být řádky nebo body (uložené jako twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Typ svislého rozestupu mezi řádky matice; jednotky svislého rozestupu mohou být řádky nebo body (uložené jako twips). |
| [getRowGap()](#getRowGap--) | Hodnota svislého rozestupu mezi řádky matice; pokud je RowGapRule nastaveno na 3 („Exactly“), jednotka se interpretuje jako twips (1/20 bodu). Pokud je RowGapRule nastaveno na 4 („Multiple“), jednotka se interpretuje jako půlřádky. |
| [setRowGap(long value)](#setRowGap-long-) | Hodnota svislého rozestupu mezi řádky matice; pokud je RowGapRule nastaveno na 3 („Exactly“), jednotka se interpretuje jako twips (1/20 bodu). Pokud je RowGapRule nastaveno na 4 („Multiple“), jednotka se interpretuje jako půlřádky. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Prvek matice |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Prvek matice |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vlastnosti řídících znaků |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Získá vodorovné zarovnání zadaného sloupce |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Nastaví vodorovné zarovnání zadaného sloupce |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Nastaví vodorovné zarovnání zadaných sloupců |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Vloží nový řádek před zadaný. Původně jsou všechny prvky v novém řádku nulové. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Vloží nový řádek po zadaném. Původně jsou všechny prvky v novém řádku nulové. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Odstraní zadaný řádek |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Vloží nový sloupec před zadaný. Původně jsou všechny prvky v novém sloupci nulové. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Vloží nový sloupec po zadaném. Původně jsou všechny prvky v novém sloupci nulové. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Odstraní zadaný sloupec |
| [getChildren()](#getChildren--) | Získá podřízené prvky |
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
> Example:
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

Skryje zástupné symboly pro prázdné prvky matice Výchozí: false

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
public final void setHidePlaceholders(boolean value)
```

Skryje zástupné symboly pro prázdné prvky matice Výchozí: false

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
public final int getBaseJustification()
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
public final void setBaseJustification(int value)
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
public final long getMinColumnWidth()
```

Minimální šířka sloupce v twips (1/20 bodu). Rozestup mezery (také nazývaný „Column Gap“ nebo „Gap Width“) se přičítá k MinColumnWidth pro určení celkového rozestupu sloupců matice (vzdálenost mezi stejnými okraji různých sloupců). Výchozí: 0.

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
public final void setMinColumnWidth(long value)
```

Minimální šířka sloupce v twips (1/20 bodu). Rozestup mezery (také nazývaný „Column Gap“ nebo „Gap Width“) se přičítá k MinColumnWidth pro určení celkového rozestupu sloupců matice (vzdálenost mezi stejnými okraji různých sloupců). Výchozí: 0.

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
public final int getColumnGapRule()
```

Typ vodorovného rozestupu mezi sloupci matice; jednotky vodorovného rozestupu mohou být ems nebo body (uložené jako twips). Výchozí: SingleSpacingGap (0)

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
public final void setColumnGapRule(int value)
```

Typ vodorovného rozestupu mezi sloupci matice; jednotky vodorovného rozestupu mohou být ems nebo body (uložené jako twips). Výchozí: SingleSpacingGap (0)

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
public final long getColumnGap()
```

Hodnota vodorovného rozestupu mezi sloupci matice; pokud je ColumnGapRule nastaveno na 3 („Exactly“), jednotka se interpretuje jako twips (1/20 bodu). Pokud je ColumnGapRule nastaveno na 4 („Multiple“), jednotka se interpretuje jako počet 0,5 em kroků. V ostatních případech je ignorováno. Výchozí: 0

--------------------

> ```
> Example:
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

Hodnota vodorovného rozestupu mezi sloupci matice; pokud je ColumnGapRule nastaveno na 3 („Exactly“), jednotka se interpretuje jako twips (1/20 bodu). Pokud je ColumnGapRule nastaveno na 4 („Multiple“), jednotka se interpretuje jako počet 0,5 em kroků. V ostatních případech je ignorováno. Výchozí: 0

--------------------

> ```
> Example:
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

Typ svislého rozestupu mezi řádky matice; jednotky svislého rozestupu mohou být řádky nebo body (uložené jako twips). Výchozí: SingleSpacingGap (0)

--------------------

> ```
> Example:
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

Typ svislého rozestupu mezi řádky matice; jednotky svislého rozestupu mohou být řádky nebo body (uložené jako twips). Výchozí: SingleSpacingGap (0)

--------------------

> ```
> Example:
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

Hodnota svislého rozestupu mezi řádky matice; pokud je RowGapRule nastaveno na 3 („Exactly“), jednotka se interpretuje jako twips (1/20 bodu). Pokud je RowGapRule nastaveno na 4 („Multiple“), jednotka se interpretuje jako půlřádky. Výchozí: 0

--------------------

> ```
> Example:
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

Hodnota svislého rozestupu mezi řádky matice; pokud je RowGapRule nastaveno na 3 („Exactly“), jednotka se interpretuje jako twips (1/20 bodu). Pokud je RowGapRule nastaveno na 4 („Multiple“), jednotka se interpretuje jako půlřádky. Výchozí: 0

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

Prvek matice

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
| row | int | Index řádku (nulově založený) pro získání položky |
| column | int | Index sloupce (nulově založený) pro získání položky |

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```

Prvek matice

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
| row | int | Index řádku (nulově založený) pro získání položky |
| column | int | Index sloupce (nulově založený) pro získání položky |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Vlastnosti řídících znaků

**Vrací:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```

Získá vodorovné zarovnání zadaného sloupce

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
| columnIndex | int | Index sloupce (nulově založený) |

**Vrací:**
int - Vodorovné zarovnání zadaného sloupce
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

Nastaví vodorovné zarovnání zadaného sloupce

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
| columnIndex | int | Index sloupce (nulově založený) |
| val | int | Nová hodnota vodorovného zarovnání zadaného sloupce |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Nastaví vodorovné zarovnání zadaných sloupců

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
| columnIndex | int | Index první sloupce (nulově založený) pro nastavení zarovnání |
| columnsCount | long | Počet sloupců, pro které se má nastavit zarovnání |
| val | int | Nová hodnota vodorovného zarovnání zadaného sloupce |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

Vloží nový řádek před zadaný. Původně jsou všechny prvky v novém řádku nulové.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| rowIndex | int | Index řádku, před kterým se vloží nový |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

Vloží nový řádek po zadaném. Původně jsou všechny prvky v novém řádku nulové.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| rowIndex | int | Index řádku po kterém se vloží nový |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```

Odstraní zadaný řádek

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
| rowIndex | int | Index řádku (nulově založený), který se má smazat. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

Vloží nový sloupec před zadaný. Původně jsou všechny prvky v novém sloupci nulové.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| columnIndex | int | Index sloupce před kterým se vloží nový |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

Vloží nový sloupec po zadaném. Původně jsou všechny prvky v novém sloupci nulové.

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
| columnIndex | int | Index sloupce po kterém se vloží nový |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```

Odstraní zadaný sloupec

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
| columnIndex | int | Index sloupce (nulové založený) pro smazání. |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Získá podřízené prvky

**Vrací:**
com.aspose.slides.IMathElement[]