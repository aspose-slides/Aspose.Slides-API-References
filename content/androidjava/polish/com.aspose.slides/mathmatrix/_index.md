---
title: MathMatrix
second_title: Aspose.Slides dla Androida - odniesienie do API Java
description: Określa obiekt Matrix składający się z elementów podrzędnych rozmieszczonych w jednym lub kilku wierszach i kolumnach.
type: docs
url: /pl/com.aspose.slides/mathmatrix/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Wszystkie implementowane interfejsy:**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

Specyfikuje obiekt Matrix, składający się z elementów podrzędnych rozmieszczonych w jednym lub kilku wierszach i kolumnach. Należy zauważyć, że macierze nie mają wbudowanych delimitatorów. Aby umieścić macierz w nawiasach, należy użyć obiektu delimitatora (IMathDelimiter). Argumenty null mogą być użyte do tworzenia przerw w macierzach.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | Inicjalizuje nową instancję klasy MathMatrix. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getRowCount()](#getRowCount--) | Liczba wierszy w macierzy |
| [getColumnCount()](#getColumnCount--) | Liczba kolumn w macierzy |
| [getHidePlaceholders()](#getHidePlaceholders--) | Ukrywa symbole zastępcze dla pustych elementów macierzy Domyślnie: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Ukrywa symbole zastępcze dla pustych elementów macierzy Domyślnie: false |
| [getBaseJustification()](#getBaseJustification--) | Określa pionowe wyrównanie względem otaczającego tekstu. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Określa pionowe wyrównanie względem otaczającego tekstu. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Minimalna szerokość kolumny w twipsach (1/20 punktu) Odstęp między kolumnami (określany również jako \u201cColumn Gap\u201d lub \u201cGap Width\u201d) jest dodawany do MinColumnWidth w celu określenia całkowitego odstępu kolumn macierzy (odległość między takimi samymi krawędziami różnych kolumn). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Minimalna szerokość kolumny w twipsach (1/20 punktu) Odstęp między kolumnami (określany również jako \u201cColumn Gap\u201d lub \u201cGap Width\u201d) jest dodawany do MinColumnWidth w celu określenia całkowitego odstępu kolumn macierzy (odległość między takimi samymi krawędziami różnych kolumn). |
| [getColumnGapRule()](#getColumnGapRule--) | Typ poziomego odstępu między kolumnami macierzy; jednostki odstępu poziomego mogą być em lub punkty (przechowywane jako twipsy). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Typ poziomego odstępu między kolumnami macierzy; jednostki odstępu poziomego mogą być em lub punkty (przechowywane jako twipsy). |
| [getColumnGap()](#getColumnGap--) | Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twips (1/20 punktu). Jeśli ColumnGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako liczba przyrostów 0.5 em. |
| [setColumnGap(long value)](#setColumnGap-long-) | Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twips (1/20 punktu). Jeśli ColumnGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako liczba przyrostów 0.5 em. |
| [getRowGapRule()](#getRowGapRule--) | Typ pionowego odstępu między wierszami macierzy; jednostki odstępu pionowego mogą być liniami lub punktami (przechowywane jako twipsy). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Typ pionowego odstępu między wierszami macierzy; jednostki odstępu pionowego mogą być liniami lub punktami (przechowywane jako twipsy). |
| [getRowGap()](#getRowGap--) | Wartość pionowego odstępu między wierszami macierzy; jeśli RowGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twips (1/20 punktu). Jeśli RowGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako pół-linii. |
| [setRowGap(long value)](#setRowGap-long-) | Wartość pionowego odstępu między wierszami macierzy; jeśli RowGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twips (1/20 punktu). Jeśli RowGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako pół-linii. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Element macierzy |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Element macierzy |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Właściwości znaków kontrolnych |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Pobiera poziome wyrównanie określonej kolumny |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Ustawia poziome wyrównanie określonej kolumny |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Ustawia poziome wyrównanie określonych kolumn |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Wstawia nowy wiersz przed określonym. Początkowo wszystkie elementy nowego wiersza są null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Wstawia nowy wiersz po określonym. Początkowo wszystkie elementy nowego wiersza są null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Usuwa określony wiersz |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Wstawia nową kolumnę przed określoną. Początkowo wszystkie elementy nowej kolumny są null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Wstawia nową kolumnę po określonej. Początkowo wszystkie elementy nowej kolumny są null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Usuwa określoną kolumnę |
| [getChildren()](#getChildren--) | Pobiera elementy potomne |

### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

Inicjalizuje nową instancję klasy MathMatrix.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| rowCount | int | liczba wierszy |
| columnCount | int | liczba kolumn |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
```

Liczba wierszy w macierzy

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Zwraca:**
int
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

Liczba kolumn w macierzy

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Zwraca:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public final boolean getHidePlaceholders()
```

Ukrywa symbole zastępcze dla pustych elementów macierzy Domyślnie: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Zwraca:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public final void setHidePlaceholders(boolean value)
```

Ukrywa symbole zastępcze dla pustych elementów macierzy Domyślnie: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

Określa pionowe wyrównanie względem otaczającego tekstu. Możliwe wartości to top, bottom i center. Domyślnie: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Zwraca:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

Określa pionowe wyrównanie względem otaczającego tekstu. Możliwe wartości to top, bottom i center. Domyślnie: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public final long getMinColumnWidth()
```

Minimalna szerokość kolumny w twipsach (1/20 punktu) Odstęp między kolumnami (określany również jako \u201cColumn Gap\u201d lub \u201cGap Width\u201d) jest dodawany do MinColumnWidth w celu określenia całkowitego odstępu kolumn macierzy (odległość między takimi samymi krawędziami różnych kolumn). Domyślnie: 0.

--------------------

> ```
> Przykład:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Zwraca:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public final void setMinColumnWidth(long value)
```

Minimalna szerokość kolumny w twipsach (1/20 punktu) Odstęp między kolumnami (określany również jako \u201cColumn Gap\u201d lub \u201cGap Width\u201d) jest dodawany do MinColumnWidth w celu określenia całkowitego odstępu kolumn macierzy (odległość między takimi samymi krawędziami różnych kolumn). Domyślnie: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public final int getColumnGapRule()
```

Typ poziomego odstępu między kolumnami macierzy; jednostki odstępu poziomego mogą być em lub punkty (przechowywane jako twipsy). Domyślnie: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Zwraca:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public final void setColumnGapRule(int value)
```

Typ poziomego odstępu między kolumnami macierzy; jednostki odstępu poziomego mogą być em lub punkty (przechowywane jako twipsy). Domyślnie: SingleSpacingGap (0)

--------------------

> ```
> Przykład:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public final long getColumnGap()
```

Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twips (1/20 punktu). Jeśli ColumnGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako liczba przyrostów 0.5 em. W innych przypadkach ignorowane. Domyślnie: 0

--------------------

> ```
> Przykład:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Zwraca:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public final void setColumnGap(long value)
```

Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twips (1/20 punktu). Jeśli ColumnGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako liczba przyrostów 0.5 em. W innych przypadkach ignorowane. Domyślnie: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public final int getRowGapRule()
```

Typ pionowego odstępu między wierszami macierzy; jednostki odstępu pionowego mogą być liniami lub punktami (przechowywane jako twipsy). Domyślnie: SingleSpacingGap (0)

--------------------

> ```
> Przykład:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Zwraca:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public final void setRowGapRule(int value)
```

Typ pionowego odstępu między wierszami macierzy; jednostki odstępu pionowego mogą być liniami lub punktami (przechowywane jako twipsy). Domyślnie: SingleSpacingGap (0)

--------------------

> ```
> Przykład:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public final long getRowGap()
```

Wartość pionowego odstępu między wierszami macierzy; jeśli RowGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twips (1/20 punktu). Jeśli RowGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako pół-linii. Domyślnie: 0

--------------------

> ```
> Przykład:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Zwraca:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public final void setRowGap(long value)
```

Wartość pionowego odstępu między wierszami macierzy; jeśli RowGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twips (1/20 punktu). Jeśli RowGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako pół-linii. Domyślnie: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```

Element macierzy

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| row | int | Indeks zerowy wiersza, z którego pobiera się element |
| column | int | Indeks zerowy kolumny, z której pobiera się element |

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```

Element macierzy

--------------------

> ```
> Przykład:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| row | int | Indeks zerowy wiersza, z którego pobiera się element |
| column | int | Indeks zerowy kolumny, z której pobiera się element |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Właściwości znaków kontrolnych

**Zwraca:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```

Pobiera poziome wyrównanie określonej kolumny

--------------------

> ```
> Przykład:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| columnIndex | int | Indeks zerowy kolumny |

**Zwraca:**
int - Poziome wyrównanie określonej kolumny
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

Ustawia poziome wyrównanie określonej kolumny

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| columnIndex | int | Indeks zerowy kolumny |
| val | int | Nowa wartość poziomego wyrównania określonej kolumny |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Ustawia poziome wyrównanie określonych kolumn

--------------------

> ```
> Przykład:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| columnIndex | int | Indeks zerowy pierwszej kolumny, której wyrównanie ma być ustawione |
| columnsCount | long | Liczba kolumn, dla których ma być określone wyrównanie |
| val | int | Nowa wartość poziomego wyrównania określonej kolumny |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

Wstawia nowy wiersz przed określonym. Początkowo wszystkie elementy nowego wiersza są null.

--------------------

> ```
> Przykład:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| rowIndex | int | Indeks wiersza, przed którym ma zostać wstawiony nowy |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

Wstawia nowy wiersz po określonym. Początkowo wszystkie elementy nowego wiersza są null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| rowIndex | int | Indeks wiersza, po którym ma zostać wstawiony nowy |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```

Usuwa określony wiersz

--------------------

> ```
> Przykład:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| rowIndex | int | Indeks zerowy wiersza, który ma zostać usunięty. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

Wstawia nową kolumnę przed określoną. Początkowo wszystkie elementy nowej kolumny są null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| columnIndex | int | Indeks kolumny, przed którą ma zostać wstawiona nowa |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

Wstawia nową kolumnę po określonej. Początkowo wszystkie elementy nowej kolumny są null.

--------------------

> ```
> Przykład:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| columnIndex | int | Indeks kolumny, po której ma zostać wstawiona nowa |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```

Usuwa określoną kolumnę

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| columnIndex | int | Indeks zerowy kolumny, która ma zostać usunięta. |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Pobiera elementy potomne

**Zwraca:**
com.aspose.slides.IMathElement[]