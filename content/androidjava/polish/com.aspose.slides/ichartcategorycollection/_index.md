---
title: IChartCategoryCollection
second_title: Aspose.Slides dla Androida poprzez odniesienie do API Java
description: Reprezentuje kolekcję
type: docs
url: /pl/com.aspose.slides/ichartcategorycollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

Reprezentuje kolekcję [IChartCategory](../../com.aspose.slides/ichartcategory)
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera element o podanym indeksie. |
| [getUseCells()](#getUseCells--) | Jeśli true, arkusz jest używany do przechowywania kategorii (ten przypadek obsługuje kategorie wielopoziomowe). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Jeśli true, arkusz jest używany do przechowywania kategorii (ten przypadek obsługuje kategorie wielopoziomowe). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Zwraca liczbę używanych poziomów grupowania kategorii. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Jeśli kategoria istnieje w kolekcji, zwraca ją. |
| [add(Object value)](#add-java.lang.Object-) | Tworzy nowy [IChartCategory](../../com.aspose.slides/ichartcategory) z wartości i dodaje go do kolekcji. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Wyszukuje określony [IChartCategory](../../com.aspose.slides/ichartcategory) i zwraca indeks zerowy pierwszego wystąpienia w całej kolekcji |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Usuwa określoną wartość. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element o podanym indeksie. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

Pobiera element o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Element o podanym indeksie.
### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

Jeśli true, arkusz jest używany do przechowywania kategorii (ten przypadek obsługuje kategorie wielopoziomowe). Jeśli false, arkusz NIE jest używany do przechowywania wartości (i ten przypadek nie obsługuje kategorii wielopoziomowych). Odczyt/zapis boolean.

**Zwraca:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

Jeśli true, arkusz jest używany do przechowywania kategorii (ten przypadek obsługuje kategorie wielopoziomowe). Jeśli false, arkusz NIE jest używany do przechowywania wartości (i ten przypadek nie obsługuje kategorii wielopoziomowych). Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

Zwraca liczbę używanych poziomów grupowania kategorii. Jest większa niż jeden dla kategorii wielopoziomowych. Tylko do odczytu int.

**Zwraca:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
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
public abstract IChartCategory add(Object value)
```

Tworzy nowy [IChartCategory](../../com.aspose.slides/ichartcategory) z wartości i dodaje go do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.Object | Wartość.

--------------------

Ta metoda dodaje arkusz o nazwie AUTO_DATA i dodaje tam wszystkie wartości. Jeśli używasz [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) do dodawania lub edytowania wartości komórek, upewnij się, że nie używasz tego arkusza. Maksymalna liczba wartości dodawanych przy użyciu tej metody nie może przekroczyć 16711680

**Zwraca:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Dodano [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

Wyszukuje określony [IChartCategory](../../com.aspose.slides/ichartcategory) i zwraca indeks zerowy pierwszego wystąpienia w całej kolekcji

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Kategoria wykresu. |

**Zwraca:**
int - Indeks zerowy pierwszego wystąpienia wartości w całej CollectionBase, jeśli znaleziono; w przeciwnym razie -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

Usuwa określoną wartość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Wartość. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa element o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks kategorii do usunięcia. |
### clear() {#clear--}
```
public abstract void clear()
```

Usuwa wszystkie elementy z kolekcji.