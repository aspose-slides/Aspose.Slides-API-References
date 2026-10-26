---
title: IMathMatrix
second_title: Aspose.Slides dla Androida za pośrednictwem referencji API Java
description: Określa obiekt Matrix składający się z elementów podrzędnych rozmieszczonych w jednym lub kilku wierszach i kolumnach.
type: docs
url: /pl/com.aspose.slides/imathmatrix/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Określa obiekt Matrix, składający się z elementów podrzędnych rozmieszczonych w jednym lub kilku wierszach i kolumnach. Należy zauważyć, że macierze nie mają wbudowanych delimitatorów. Aby umieścić macierz w nawiasach, należy użyć obiektu delimitera (IMathDelimiter). Argumenty null mogą być użyte do tworzenia przerw w macierzach.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | Elementy macierzy |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Elementy macierzy |
| [getRowCount()](#getRowCount--) | Liczba wierszy w macierzy |
| [getColumnCount()](#getColumnCount--) | Liczba kolumn w macierzy |
| [getHidePlaceholders()](#getHidePlaceholders--) | Ukryj symbole zastępcze dla pustych elementów macierzy Domyślnie: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Ukryj symbole zastępcze dla pustych elementów macierzy Domyślnie: false |
| [getBaseJustification()](#getBaseJustification--) | Określa pionowe justowanie względem otaczającego tekstu. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Określa pionowe justowanie względem otaczającego tekstu. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Minimalna szerokość kolumny w jednostkach twip (1/20 punktu). Odstęp szczeliny (oznaczany również jako \\u201cColumn Gap\\u201d lub \\u201cGap Width\\u201d) jest dodawany do MinColumnWidth, aby określić całkowite odstępy kolumn macierzy (odległość między tymi samymi krawędziami różnych kolumn). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Minimalna szerokość kolumny w jednostkach twip (1/20 punktu). Odstęp szczeliny (oznaczany również jako \\u201cColumn Gap\\u201d lub \\u201cGap Width\\u201d) jest dodawany do MinColumnWidth, aby określić całkowite odstępy kolumn macierzy (odległość między tymi samymi krawędziami różnych kolumn). |
| [getColumnGapRule()](#getColumnGapRule--) | Typ poziomego odstępu między kolumnami macierzy; jednostki poziomego odstępu mogą być em lub punkty (przechowywane jako twipy). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Typ poziomego odstępu między kolumnami macierzy; jednostki poziomego odstępu mogą być em lub punkty (przechowywane jako twipy). |
| [getColumnGap()](#getColumnGap--) | Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twipy (1/20 punktu). Jeśli ColumnGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako liczba przyrostów 0,5 em. |
| [setColumnGap(long value)](#setColumnGap-long-) | Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twipy (1/20 punktu). Jeśli ColumnGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako liczba przyrostów 0,5 em. |
| [getRowGapRule()](#getRowGapRule--) | Typ pionowego odstępu między wierszami macierzy; jednostki pionowego odstępu mogą być wiersze lub punkty (przechowywane jako twipy). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Typ pionowego odstępu między wierszami macierzy; jednostki pionowego odstępu mogą być wiersze lub punkty (przechowywane jako twipy). |
| [getRowGap()](#getRowGap--) | Wartość pionowego odstępu między wierszami macierzy; jeśli RowGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twipy (1/20 punktu). Jeśli RowGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako półwiersze. |
| [setRowGap(long value)](#setRowGap-long-) | Wartość pionowego odstępu między wierszami macierzy; jeśli RowGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twipy (1/20 punktu). Jeśli RowGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako półwiersze. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Pobierz poziome wyrównanie określonej kolumny |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Ustaw poziome wyrównanie określonej kolumny |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Ustaw poziome wyrównanie określonych kolumn |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Wstaw nowy wiersz przed określonym. Początkowo wszystkie elementy w nowym wierszu są null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Wstaw nowy wiersz po określonym. Początkowo wszystkie elementy w nowym wierszu są null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Usuwa określony wiersz |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Wstaw nową kolumnę przed określoną. Początkowo wszystkie elementy w nowej kolumnie są null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Wstaw nową kolumnę po określonej. Początkowo wszystkie elementy w nowej kolumnie są null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Usuwa określoną kolumnę |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

Elementy macierzy

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
| row | int | Indeks zerowy wiersza, z którego pobierany jest element |
| column | int | Indeks zerowy kolumny, z której pobierany jest element |

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement

### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```

Elementy macierzy

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
| row | int | Indeks zerowy wiersza, z którego pobierany jest element |
| column | int | Indeks zerowy kolumny, z której pobierany jest element |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
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
public abstract int getColumnCount()
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
public abstract boolean getHidePlaceholders()
```

Ukryj symbole zastępcze dla pustych elementów macierzy Domyślnie: false

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
public abstract void setHidePlaceholders(boolean value)
```

Ukryj symbole zastępcze dla pustych elementów macierzy Domyślnie: false

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
public abstract int getBaseJustification()
```

Określa pionowe justowanie względem otaczającego tekstu. Możliwe wartości to top, bottom i center. Domyślnie: Center

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
public abstract void setBaseJustification(int value)
```

Określa pionowe justowanie względem otaczającego tekstu. Możliwe wartości to top, bottom i center. Domyślnie: Center

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
public abstract long getMinColumnWidth()
```

Minimalna szerokość kolumny w jednostkach twip (1/20 punktu). Odstęp szczeliny (oznaczany również jako \\u201cColumn Gap\\u201d lub \\u201cGap Width\\u201d) jest dodawany do MinColumnWidth, aby określić całkowite odstępy kolumn macierzy (odległość między tymi samymi krawędziami różnych kolumn). Domyślnie: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Zwraca:**
long

### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```

Minimalna szerokość kolumny w jednostkach twip (1/20 punktu). Odstęp szczeliny (oznaczany również jako \\u201cColumn Gap\\u201d lub \\u201cGap Width\\u201d) jest dodawany do MinColumnWidth, aby określić całkowite odstępy kolumn macierzy (odległość między tymi samymi krawędziami różnych kolumn). Domyślnie: 0.

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
public abstract int getColumnGapRule()
```

Typ poziomego odstępu między kolumnami macierzy; jednostki poziomego odstępu mogą być em lub punkty (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0)

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
public abstract void setColumnGapRule(int value)
```

Typ poziomego odstępu między kolumnami macierzy; jednostki poziomego odstępu mogą być em lub punkty (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0)

--------------------

> ```
> Example:
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
public abstract long getColumnGap()
```

Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twipy (1/20 punktu). Jeśli ColumnGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako liczba przyrostów 0,5 em. W innych przypadkach ignorowane. Domyślnie: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Zwraca:**
long

### setColumnGap(long value) {#setColumnGap-long-}
```
public abstract void setColumnGap(long value)
```

Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twipy (1/20 punktu). Jeśli ColumnGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako liczba przyrostów 0,5 em. W innych przypadkach ignorowane. Domyślnie: 0

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
public abstract int getRowGapRule()
```

Typ pionowego odstępu między wierszami macierzy; jednostki pionowego odstępu mogą być wiersze lub punkty (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Zwraca:**
int

### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```

Typ pionowego odstępu między wierszami macierzy; jednostki pionowego odstępu mogą być wiersze lub punkty (przechowywane jako twipy). Domyślnie: SingleSpacingGap (0)

--------------------

> ```
> Example:
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
public abstract long getRowGap()
```

Wartość pionowego odstępu między wierszami macierzy; jeśli RowGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twipy (1/20 punktu). Jeśli RowGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako półwiersze. Domyślnie: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Zwraca:**
long

### setRowGap(long value) {#setRowGap-long-}
```
public abstract void setRowGap(long value)
```

Wartość pionowego odstępu między wierszami macierzy; jeśli RowGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twipy (1/20 punktu). Jeśli RowGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako półwiersze. Domyślnie: 0

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

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

Pobierz poziome wyrównanie określonej kolumny

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| columnIndex | int | Indeks zerowy kolumny |

**Zwraca:**
int - Horizontal Alignment of specified column

### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

Ustaw poziome wyrównanie określonej kolumny

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
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Ustaw poziome wyrównanie określonych kolumn

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| columnIndex | int | Indeks zerowy pierwszej kolumny, której wyrównanie ma być ustawione |
| columnsCount | long | Liczba kolumn, dla których ma zostać określone wyrównanie |
| val | int | Nowa wartość poziomego wyrównania określonej kolumny |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

Wstaw nowy wiersz przed określonym. Początkowo wszystkie elementy w nowym wierszu są null.

--------------------

> ```
> Example:
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
public abstract void insertRowAfter(int rowIndex)
```

Wstaw nowy wiersz po określonym. Początkowo wszystkie elementy w nowym wierszu są null.

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
public abstract void deleteRow(int rowIndex)
```

Usuwa określony wiersz

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| rowIndex | int | Indeks zerowy wiersza do usunięcia. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

Wstaw nową kolumnę przed określoną. Początkowo wszystkie elementy w nowej kolumnie są null.

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
public abstract void insertColumnAfter(int columnIndex)
```

Wstaw nową kolumnę po określonej. Początkowo wszystkie elementy w nowej kolumnie są null.

--------------------

> ```
> Example:
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
public abstract void deleteColumn(int columnIndex)
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
| columnIndex | int | Indeks zerowy kolumny do usunięcia. |