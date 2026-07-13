---
title: RowCollection
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Reprezentuje kolekcję wierszy tabeli.
type: docs
url: /pl/com.aspose.slides/rowcollection/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

Reprezentuje kolekcję wierszy tabeli.
## Metody

| Metoda | Opis |
| --- | --- |
| [size()](#size--) | Pobiera liczbę wierszy rzeczywiście zawartych w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Zwraca wiersz o określonym indeksie. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Tworzy kopię określonego wiersza szablonu i wstawia ją na końcu tabeli. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Tworzy kopię określonego wiersza szablonu i wstawia ją w określonym miejscu w tabeli. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Usuwa wiersz w określonej pozycji z tabeli. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator języka Java dla całej kolekcji. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wszystkie elementy z kolekcji do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość określającą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
### size() {#size--}
```
public final int size()
```


Pobiera liczbę wierszy rzeczywiście zawartych w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```


Zwraca wiersz o określonym indeksie. Tylko do odczytu [Row](../../com.aspose.slides/row).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```


Tworzy kopię określonego wiersza szablonu i wstawia ją na końcu tabeli.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Wiersz używany jako szablon. |
| withAttachedRows | boolean | True, aby skopiować również wszystkie wiersze dołączone do wiersza szablonu. |

**Zwraca:**
com.aspose.slides.IRow[] - Dodane wiersze.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


Tworzy kopię określonego wiersza szablonu i wstawia ją w określonym miejscu w tabeli.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowego wiersza. |
| templ | [IRow](../../com.aspose.slides/irow) | Wiersz używany jako szablon. |
| withAttachedRows | boolean | True, aby skopiować również wszystkie wiersze dołączone do wiersza szablonu. |

**Zwraca:**
com.aspose.slides.IRow[] - Wstawione wiersze.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Usuwa wiersz w określonej pozycji z tabeli.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| firstRowIndex | int | Indeks wiersza do usunięcia. |
| withAttachedRows | boolean | True, aby usunąć również wszystkie dołączone wiersze. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```


Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - IGenericEnumerator, który może być użyty do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```


Zwraca iterator języka Java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - java.util.Iterator dla całej kolekcji.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopiuje wszystkie elementy z kolekcji do określonej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica docelowa. |
| index | int | Indeks początkowy w tablicy docelowej. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Zwraca wartość określającą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). Tylko do odczytu boolean.

**Zwraca:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Zwraca korzeń synchronizacji. Tylko do odczytu Object.

**Zwraca:**
java.lang.Object