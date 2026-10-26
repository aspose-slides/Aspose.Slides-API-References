---
title: ChartCategoryCollection
second_title: Aspose.Slides dla Java – odniesienie API
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
| [get_Item(int index)](#get-Item-int-) | Pobiera element pod określonym indeksem. |
| [getUseCells()](#getUseCells--) | Jeśli true, arkusz jest używany do przechowywania kategorii (ten przypadek obsługuje kategorie wielopoziomowe). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Jeśli true, arkusz jest używany do przechowywania kategorii (ten przypadek obsługuje kategorie wielopoziomowe). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Zwraca liczbę użytych poziomów grupowania kategorii. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Jeśli kategoria istnieje w kolekcji, zwraca ją. |
| [add(Object value)](#add-java.lang.Object-) | Tworzy nowy [ChartCategory](../../com.aspose.slides/chartcategory) z wartości i dodaje go do kolekcji. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Wyszukuje określony [ChartCategory](../../com.aspose.slides/chartcategory) i zwraca indeks zerowy pierwszego wystąpienia w całej kolekcji. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Usuwa określoną wartość. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element pod podanym indeksem. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
| [iterator()](#iterator--) | Zwraca enumerator iterujący po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator java dla całej kolekcji. |
| [size()](#size--) | Zwraca liczbę elementów w kolekcji. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wszystkie elementy kolekcji do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do Listy jest zsynchronizowany (wątkowo bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca obiekt, który może być użyty do synchronizacji dostępu do kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```


Pobiera element pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Element pod określonym indeksem.
### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```


Jeśli true, arkusz jest używany do przechowywania kategorii (ten przypadek obsługuje kategorie wielopoziomowe). Jeśli false, arkusz NIE jest używany do przechowywania wartości (i ten przypadek nie obsługuje kategorii wielopoziomowych). Odczyt/zapis boolean.

**Zwraca:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```


Jeśli true, arkusz jest używany do przechowywania kategorii (ten przypadek obsługuje kategorie wielopoziomowe). Jeśli false, arkusz NIE jest używany do przechowywania wartości (i ten przypadek nie obsługuje kategorii wielopoziomowych). Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```


Zwraca liczbę użytych poziomów grupowania kategorii. Jest większa niż jeden dla kategorii wielopoziomowych. Tylko do odczytu int.

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
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Komórka używana do tworzenia kategorii wykresu. |

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
| value | java.lang.Object | Wartość. |

--------------------

Ta metoda dodaje arkusz o nazwie AUTO_DATA i dodaje wszystkie wartości do niego. Jeśli używasz [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) do dodawania lub edytowania wartości komórek, upewnij się, że nie używasz tego arkusza. Maksymalna liczba wartości dodawanych przy użyciu tej metody nie może przekroczyć 16711680 |

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
int - Indeks zerowy pierwszego wystąpienia wartości w całej CollectionBase, jeśli znaleziono; w przeciwnym razie -1.
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


Usuwa element pod podanym indeksem.

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


Zwraca iterator java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - java.util.Iterator dla całej kolekcji.
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


Zwraca wartość wskazującą, czy dostęp do Listy jest zsynchronizowany (wątkowo bezpieczny). Tylko do odczytu boolean.

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