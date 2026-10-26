---
title: TabCollection
second_title: Aspose.Slides dla Java – dokumentacja API
description: Reprezentuje kolekcję zakładek.
type: docs
url: /pl/com.aspose.slides/tabcollection/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

Reprezentuje kolekcję Tab.

## Metody

| Metoda | Opis |
| --- | --- |
| [size()](#size--) | Pobiera liczbę elementów faktycznie zawartych w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Pobiera element znajdujący się pod określonym indeksem. |
| [add(double position, int align)](#add-double-int-) | Dodaje Tab do kolekcji. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Dodaje Tab do kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element pod określonym indeksem w kolekcji. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy dwie instancje TabsEx są równe. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator java dla całej kolekcji. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wszystkie elementy z kolekcji do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
### size() {#size--}
```
public final int size()
```

Pobiera liczbę elementów faktycznie zawartych w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```

Pobiera element znajdujący się pod określonym indeksem. Tylko do odczytu [Tab](../../com.aspose.slides/tab).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```

Dodaje Tab do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**Zwraca:**
[ITab](../../com.aspose.slides/itab) - Dodana zakładka.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```

Dodaje Tab do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Obiekt Tab, który ma zostać dodany na końcu kolekcji. |

**Zwraca:**
int - Indeks, pod którym dodano zakładkę.
### clear() {#clear--}
```
public final void clear()
```

Usuwa wszystkie elementy z kolekcji.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Usuwa element pod określonym indeksem w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu do usunięcia. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Określa, czy dwie instancje TabsEx są równe.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | TabsEx do porównania z bieżącym TabsEx. |

**Zwraca:**
boolean - **true**, jeśli podany TabsEx jest równy bieżącemu TabsEx; w przeciwnym razie **false**.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```

Zwraca iterator java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - An java.util.Iterator for the entire collection.
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