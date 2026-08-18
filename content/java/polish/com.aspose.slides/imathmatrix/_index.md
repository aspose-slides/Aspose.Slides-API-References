---
title: IMathMatrix
second_title: Aspose.Slides dla Java – Dokumentacja API
description: Określa obiekt Matrix składający się z elementów podrzędnych rozmieszczonych w jednym lub kilku wierszach i kolumnach.
type: docs
url: /pl/com.aspose.slides/imathmatrix/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Określa obiekt Matrix, składający się z elementów podrzędnych rozmieszczonych w jednym lub kilku wierszach i kolumnach. Należy zauważyć, że macierze nie mają wbudowanych delimitatorów. Aby umieścić macierz w nawiasach, należy użyć obiektu delimitatora (IMathDelimiter). Argumenty o wartości null mogą być użyte do tworzenia przerw w macierzach.

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
| [getMinColumnWidth()](#getMinColumnWidth--) | Minimalna szerokość kolumny w twipsach (1/20 punktu). Odstęp między kolumnami (nazywany także „Column Gap” lub „Gap Width”) jest dodawany do MinColumnWidth w celu określenia całkowitego odstępu kolumn w macierzy (odległość między tymi samymi krawędziami różnych kolumn). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Minimalna szerokość kolumny w twipsach (1/20 punktu). Odstęp między kolumnami (nazywany także „Column Gap” lub „Gap Width”) jest dodawany do MinColumnWidth w celu określenia całkowitego odstępu kolumn w macierzy (odległość między tymi samymi krawędziami różnych kolumn). |
| [getColumnGapRule()](#getColumnGapRule--) | Typ poziomego odstępu między kolumnami macierzy; Jednostki poziomego odstępu mogą być ems lub punkty (przechowywane jako twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | Typ poziomego odstępu między kolumnami macierzy; Jednostki poziomego odstępu mogą być ems lub punkty (przechowywane jako twips). |
| [getColumnGap()](#getColumnGap--) | Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twips (1/20 punktu). Jeśli ColumnGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako liczba przyrostów po 0,5 em. W innych przypadkach ignorowane. Domyślnie: 0 |
| [setColumnGap(long value)](#setColumnGap-long-) | Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twips (1/20 punktu). Jeśli ColumnGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako liczba przyrostów po 0,5 em. W innych przypadkach ignorowane. Domyślnie: 0 |
| [getRowGapRule()](#getRowGapRule--) | Typ pionowego odstępu między wierszami macierzy; Jednostki pionowego odstępu mogą być linie lub punkty (przechowywane jako twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | Typ pionowego odstępu między wierszami macierzy; Jednostki pionowego odstępu mogą być linie lub punkty (przechowywane jako twips). |
| [getRowGap()](#getRowGap--) | Wartość pionowego odstępu między wierszami macierzy; jeśli RowGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twips (1/20 punktu). Jeśli RowGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako pół-linie. Domyślnie: 0 |
| [setRowGap(long value)](#setRowGap-long-) | Wartość pionowego odstępu między wierszami macierzy; jeśli RowGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twips (1/20 punktu). Jeśli RowGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako pół-linie. Domyślnie: 0 |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Pobierz wyrównanie poziome określonej kolumny |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Ustaw wyrównanie poziome określonej kolumny |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Ustaw wyrównanie poziome określonych kolumn |
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
| row | int | Indeks wiersza zaczynający się od zera |
| column | int | Indeks kolumny zaczynający się od zera |

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
| row | int | Indeks wiersza zaczynający się od zera |
| column | int | Indeks kolumny zaczynający się od zera |
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

Minimalna szerokość kolumny w twipsach (1/20 punktu). Odstęp między kolumnami (nazywany także „Column Gap” lub „Gap Width”) jest dodawany do MinColumnWidth w celu określenia całkowitego odstępu kolumn w macierzy (odległość między tymi samymi krawędziami różnych kolumn). Domyślnie: 0.

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
public abstract void setMinColumnWidth(long value)
```

Minimalna szerokość kolumny w twipsach (1/20 punktu). Odstęp między kolumnami (nazywany także „Column Gap” lub „Gap Width”) jest dodawany do MinColumnWidth w celu określenia całkowitego odstępu kolumn w macierzy (odległość między tymi samymi krawędziami różnych kolumn). Domyślnie: 0.

--------------------

> ```
> Przykład:
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

Typ poziomego odstępu między kolumnami macierzy; Jednostki poziomego odstępu mogą być ems lub punkty (przechowywane jako twips). Domyślnie: SingleSpacingGap (0)

--------------------

> ```
> Przykład:
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

Typ poziomego odstępu między kolumnami macierzy; Jednostki poziomego odstępu mogą być ems lub punkty (przechowywane jako twips). Domyślnie: SingleSpacingGap (0)

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
public abstract long getColumnGap()
```

Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twips (1/20 punktu). Jeśli ColumnGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako liczba przyrostów po 0,5 em. W innych przypadkach ignorowane. Domyślnie: 0

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
public abstract void setColumnGap(long value)
```

Wartość poziomego odstępu między kolumnami macierzy; jeśli ColumnGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twips (1/20 punktu). Jeśli ColumnGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako liczba przyrostów po 0,5 em. W innych przypadkach ignorowane. Domyślnie: 0

--------------------

> ```
> Przykład:
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

Typ pionowego odstępu między wierszami macierzy; Jednostki pionowego odstępu mogą być linie lub punkty (przechowywane jako twips). Domyślnie: SingleSpacingGap (0)

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
public abstract void setRowGapRule(int value)
```

Typ pionowego odstępu między wierszami macierzy; Jednostki pionowego odstępu mogą być linie lub punkty (przechowywane jako twips). Domyślnie: SingleSpacingGap (0)

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
public abstract long getRowGap()
```

Wartość pionowego odstępu między wierszami macierzy; jeśli RowGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twips (1/20 punktu). Jeśli RowGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako pół-linie. Domyślnie: 0

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
public abstract void setRowGap(long value)
```

Wartość pionowego odstępu między wierszami macierzy; jeśli RowGapRule ma wartość 3 („Exactly”), jednostka jest interpretowana jako twips (1/20 punktu). Jeśli RowGapRule ma wartość 4 („Multiple”), jednostka jest interpretowana jako pół-linie. Domyślnie: 0

--------------------

> ```
> Przykład:
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

Pobierz wyrównanie poziome określonej kolumny

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
| columnIndex | int | Indeks kolumny zaczynający się od zera |

**Zwraca:**
int - Wyrównanie poziome określonej kolumny

### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

Ustaw wyrównanie poziome określonej kolumny

--------------------

> ```
> Przykład:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| columnIndex | int | Indeks kolumny zaczynający się od zera |
| val | int | Nowa wartość wyrównania poziomego określonej kolumny |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

Ustaw wyrównanie poziome określonych kolumn

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
| columnIndex | int | Indeks pierwszej kolumny, której wyrównanie ma być ustawione |
| columnsCount | long | Liczba kolumn, dla których ma zostać określone wyrównanie |
| val | int | Nowa wartość wyrównania poziomego określonej kolumny |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

Wstaw nowy wiersz przed określonym. Początkowo wszystkie elementy w nowym wierszu są null.

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
| rowIndex | int | Indeks wiersza przed którym ma zostać wstawiony nowy |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

Wstaw nowy wiersz po określonym. Początkowo wszystkie elementy w nowym wierszu są null.

--------------------

> ```
> Przykład:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| rowIndex | int | Indeks wiersza po którym ma zostać wstawiony nowy |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
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
| rowIndex | int | Indeks wiersza zaczynający się od zera, który ma zostać usunięty. |

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
| columnIndex | int | Indeks kolumny przed którą ma być wstawiona nowa |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

Wstaw nową kolumnę po określonej. Początkowo wszystkie elementy w nowej kolumnie są null.

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
| columnIndex | int | Indeks kolumny po której ma być wstawiona nowa |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```

Usuwa określoną kolumnę

--------------------

> ```
> Przykład:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| columnIndex | int | Indeks kolumny zaczynający się od zera, którą ma zostać usunięta. |