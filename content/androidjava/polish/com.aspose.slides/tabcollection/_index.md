---
title: TabCollection
second_title: Aspose.Slides dla Androida za pośrednictwem dokumentacji API Java
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

Reprezentuje kolekcję zakładek.
## Metody

| Metoda | Opis |
| --- | --- |
| [size()](#size--) | Zwraca liczbę elementów faktycznie znajdujących się w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Zwraca element o określonym indeksie. |
| [add(double position, int align)](#add-double-int-) | Dodaje zakładkę do kolekcji. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Dodaje zakładkę do kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element o określonym indeksie w kolekcji. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy dwa wystąpienia TabsEx są równe. |
| [iterator()](#iterator--) | Zwraca enumerator iterujący po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator java dla całej kolekcji. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wszystkie elementy z kolekcji do podanej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
### size() {#size--}
```
public final int size()
```


Zwraca liczbę elementów faktycznie znajdujących się w kolekcji. int tylko do odczytu.

**Zwraca:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```


Zwraca element o określonym indeksie. [Tab](../../com.aspose.slides/tab) tylko do odczytu.

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


Dodaje zakładkę do kolekcji.

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


Dodaje zakładkę do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Obiekt Tab, który ma zostać dodany na końcu kolekcji. |

**Zwraca:**
int - Indeks, pod którym zakładka została dodana.
### clear() {#clear--}
```
public final void clear()
```


Usuwa wszystkie elementy z kolekcji.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Usuwa element o określonym indeksie w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu do usunięcia. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Zwraca obiekt Parent_Immediate. IDOMObject tylko do odczytu.

**Zwraca:**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Określa, czy dwa wystąpienia TabsEx są równe.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | TabsEx, który ma być porównany z bieżącym TabsEx. |

**Zwraca:**
boolean - **true**, jeśli podany TabsEx jest równy bieżącemu TabsEx; w przeciwnym razie **false**.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```


Zwraca enumerator iterujący po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - IGenericEnumerator, który może być użyty do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```


Zwraca iterator java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - java.util.Iterator dla całej kolekcji.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopiuje wszystkie elementy z kolekcji do podanej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica docelowa. |
| index | int | Początkowy indeks w tablicy docelowej. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). boolean tylko do odczytu.

**Zwraca:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Zwraca korzeń synchronizacji. Object tylko do odczytu.

**Zwraca:**
java.lang.Object