---
title: ColumnCollection
second_title: Aspose.Slides dla Androida – odniesienie API w Javie
description: Reprezentuje kolekcję kolumn w tabeli.
type: docs
url: /pl/com.aspose.slides/columncollection/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

Reprezentuje kolekcję kolumn w tabeli.
## Metody

| Metoda | Opis |
| --- | --- |
| [size()](#size--) | Zwraca liczbę kolumn w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Zwraca kolumnę o podanym indeksie. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Tworzy kopię określonego szablonu wiersza i wstawia ją na koniec tabeli. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Tworzy kopię określonego szablonu kolumny i wstawia ją w podanej pozycji w tabeli. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Usuwa kolumnę w określonej pozycji z tabeli. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator java dla całej kolekcji. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wszystkie elementy z kolekcji do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest synchronizowany (wątkowo bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
### size() {#size--}
```
public final int size()
```


Zwraca liczbę kolumn w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```


Zwraca kolumnę o podanym indeksie. Tylko do odczytu [Column](../../com.aspose.slides/column).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


Tworzy kopię określonego szablonu wiersza i wstawia ją na koniec tabeli.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Kolumna używana jako szablon. |
| withAttachedColumns | boolean | Prawda, aby skopiować także wszystkie kolumny dołączone do szablonu wiersza. |

**Zwraca:**
com.aspose.slides.IColumn[] - Dodane kolumny.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


Tworzy kopię określonego szablonu kolumny i wstawia ją w podanej pozycji w tabeli.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowej kolumny. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Kolumna używana jako szablon. |
| withAttachedColumns | boolean | Prawda, aby skopiować także wszystkie kolumny dołączone do szablonu kolumny. |

**Zwraca:**
com.aspose.slides.IColumn[] - Wstawione kolumny.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


Usuwa kolumnę w określonej pozycji z tabeli.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| firstColumnIndex | int | Indeks kolumny do usunięcia. |
| withAttachedRows | boolean | Prawda, aby usunąć także wszystkie dołączone kolumny. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```


Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - IGenericEnumerator, który może być użyty do iteracji przez kolekcję.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```


Zwraca iterator java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - java.util.Iterator dla całej kolekcji.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopiuje wszystkie elementy z kolekcji do określonej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica docelowa. |
| index | int | Początkowy indeks w tablicy docelowej. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Zwraca wartość wskazującą, czy dostęp do kolekcji jest synchronizowany (wątkowo bezpieczny). Tylko do odczytu boolean.

**Zwraca:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Zwraca korzeń synchronizacji. Tylko do odczytu Object.

**Zwraca:**
java.lang.Object