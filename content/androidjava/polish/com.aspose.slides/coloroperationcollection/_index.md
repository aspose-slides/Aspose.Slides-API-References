---
title: ColorOperationCollection
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Reprezentuje kolekcję operacji transformacji kolorów.
type: docs
url: /pl/com.aspose.slides/coloroperationcollection/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

Represents a collection of color transform operations.
## Metody

| Metoda | Opis |
| --- | --- |
| [size()](#size--) | Zwraca liczbę operacji w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Zwraca lub ustawia operację pod określonym indeksem. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Zwraca lub ustawia operację pod określonym indeksem. |
| [add(int operation, float parameter)](#add-int-float-) | Dodaje nową operację na koniec kolekcji. |
| [add(int operation)](#add-int-) | Dodaje nową operację na koniec kolekcji. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Wstawia nową operację do kolekcji. |
| [insert(int position, int operation)](#insert-int-int-) | Wstawia nową operację do kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa operację koloru z kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie operacje koloru. |
| [iterator()](#iterator--) | Zwraca enumerator iterujący po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator java dla całej kolekcji. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wszystkie elementy z kolekcji do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
| [deepClone()](#deepClone--) | Tworzy kopię kolekcji ColorOperationCollection. |
| [cloneT()](#cloneT--) | Klonuje bieżący obiekt |

### size() {#size--}
```
public final int size()
```

Zwraca liczbę operacji w kolekcji. Tylko do odczytu int.

**Zwraca:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

Zwraca lub ustawia operację pod określonym indeksem. Do odczytu/zapisu [ColorOperation](../../com.aspose.slides/coloroperation).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IColorOperation](../../com.aspose.slides/icoloroperation)

### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

Zwraca lub ustawia operację pod określonym indeksem. Do odczytu/zapisu [ColorOperation](../../com.aspose.slides/coloroperation).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

Dodaje nową operację na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| operation | int | Typ operacji. |
| parameter | float | Parametr operacji. |

**Zwraca:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Dodana operacja.

### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

Dodaje nową operację na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| operation | int | Typ operacji. |

**Zwraca:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Dodana operacja.

### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

Wstawia nową operację do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| position | int | Indeks, pod którym operacja zostanie wstawiona. |
| operation | int | Typ operacji. |
| parameter | float | Parametr operacji. |

**Zwraca:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Wstawiona operacja.

### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

Wstawia nową operację do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| position | int | Indeks, pod którym operacja zostanie wstawiona. |
| operation | int | Typ operacji. |

**Zwraca:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Wstawiona operacja.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Usuwa operację koloru z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks operacji koloru do usunięcia. |

### clear() {#clear--}
```
public final void clear()
```

Usuwa wszystkie operacje koloru.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

Zwraca enumerator iterujący po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - IGenericEnumerator, który można użyć do iteracji po kolekcji.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

Zwraca iterator java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Iterator java.util.Iterator dla całej kolekcji.

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

Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). Tylko do odczytu boolean.

**Zwraca:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Zwraca korzeń synchronizacji. Tylko do odczytu Object.

**Zwraca:**
java.lang.Object

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Tworzy kopię kolekcji ColorOperationCollection.

**Zwraca:**
java.lang.Object - Nowa [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) kolekcja.

### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

Klonuje bieżący obiekt

**Zwraca:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - Klon