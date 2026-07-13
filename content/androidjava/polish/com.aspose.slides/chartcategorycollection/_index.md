---
title: ChartCategoryCollection
second_title: Aspose.Slides dla Androida – dokumentacja Java API
description: Reprezentuje kolekcję
type: docs
url: /pl/com.aspose.slides/chartcategorycollection/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

Reprezentuje kolekcję [ChartCategory](../../com.aspose.slides/chartcategory)
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera element o określonym indeksie. |
| [getUseCells()](#getUseCells--) | Jeśli true, to arkusz jest używany do przechowywania kategorii (ten przypadek obsługuje wielopoziomowe kategorie). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Jeśli true, to arkusz jest używany do przechowywania kategorii (ten przypadek obsługuje wielopoziomowe kategorie). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Zwraca liczbę poziomów grupowania kategorii używanych. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Jeśli kategoria istnieje w kolekcji, zwraca ją. |
| [add(Object value)](#add-java.lang.Object-) | Tworzy nowy [ChartCategory](../../com.aspose.slides/chartcategory) z wartości i dodaje go do kolekcji. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Wyszukuje określony [ChartCategory](../../com.aspose.slides/chartcategory) i zwraca indeks zerowy pierwszego wystąpienia w całej kolekcji. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Usuwa określoną wartość. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element o podanym indeksie. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
| [iterator()](#iterator--) | Zwraca enumerator iterujący po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator języka Java dla całej kolekcji. |
| [size()](#size--) | Zwraca liczbę elementów w kolekcji. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wszystkie elementy kolekcji do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do listy jest zsynchronizowany (wątkowo bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca obiekt, który może być użyty do synchronizacji dostępu do kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

Pobiera element o określonym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Element o określonym indeksie.
### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

Jeśli true, to arkusz jest używany do przechowywania kategorii (ten przypadek obsługuje wielopoziomowe kategorie). Jeśli false, to arkusz NIE jest używany do przechowywania wartości (i ten przypadek nie obsługuje wielopoziomowych kategorii). Odczyt/zapis boolean.

**Zwraca:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

Jeśli true, to arkusz jest używany do przechowywania kategorii (ten przypadek obsługuje wielopoziomowe kategorie). Jeśli false, to arkusz NIE jest używany do przechowywania wartości (i ten przypadek nie obsługuje wielopoziomowych kategorii). Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

Zwraca liczbę używanych poziomów grupowania kategorii. Jest większa niż jeden dla wielopoziomowych kategorii. Tylko do odczytu int.

**Zwraca:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

Jeśli kategoria istnieje w kolekcji, zwraca ją. W przeciwnym razie tworzy nową kategorię wykresu z [IChartDataCell](../../com.aspose.slides/ichartdatacell) i dodaje ją do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Komórka używana do utworzenia kategorii wykresu. |

**Zwraca:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Dodana lub istniejąca kategoria.
### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

Tworzy nowy [ChartCategory](../../com.aspose.slides/chartcategory) z wartości i dodaje go do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.Object | Wartość.

--------------------

Ta metoda dodaje arkusz o nazwie AUTO_DATA i umieszcza w nim wszystkie wartości. Jeśli używasz [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) do dodawania lub edytowania wartości komórek, upewnij się, że nie używasz tego arkusza. Maksymalna liczba wartości dodawanych przy użyciu tej metody nie może przekroczyć 16711680

**Zwraca:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Dodano [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

Wyszukuje określony [ChartCategory](../../com.aspose.slides/chartcategory) i zwraca indeks zerowy pierwszego wystąpienia w całej kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Kategoria wykresu. |

**Zwraca:**
int - Zerowy indeks pierwszego wystąpienia wartości w całej CollectionBase, jeśli znaleziono; w przeciwnym razie -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

Usuwa określoną wartość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Wartość. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Usuwa element o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks kategorii do usunięcia. |
### clear() {#clear--}
```
public final void clear()
```

Usuwa wszystkie elementy z kolekcji.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

Zwraca enumerator iterujący po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - IGenericEnumerator, który może być użyty do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

Zwraca iterator języka Java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Iterator java.util.Iterator dla całej kolekcji.
### size() {#size--}
```
public final int size()
```

Zwraca liczbę elementów w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiuje wszystkie elementy kolekcji do określonej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica docelowa. |
| index | int | Początkowy indeks w tablicy. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Zwraca wartość wskazującą, czy dostęp do listy jest zsynchronizowany (wątkowo bezpieczny). Tylko do odczytu boolean.

**Zwraca:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Zwraca obiekt, który może być użyty do synchronizacji dostępu do kolekcji. Tylko do odczytu Object.

Zwraca korzeń synchronizacji. Tylko do odczytu Object.

**Zwraca:**
java.lang.Object