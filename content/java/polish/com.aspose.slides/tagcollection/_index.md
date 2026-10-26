---
title: TagCollection
second_title: Aspose.Slides dla Java API Reference
description: Reprezentuje kolekcję tagów – pary łańcuchów definiowane przez użytkownika
type: docs
url: /pl/com.aspose.slides/tagcollection/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

Reprezentuje kolekcję tagów (pary ciągów definiowane przez użytkownika)

--------------------

> ```
> The following example shows how to add a tag to a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ITagCollection tags = pres.getCustomData().getTags();
>      pres.getCustomData().getTags().add("MyTag", "My Tag Value");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Metody

| Metoda | Opis |
| --- | --- |
| [size()](#size--) | Zwraca liczbę tagów w kolekcji. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Dodaje nowy tag do kolekcji. |
| [remove(String name)](#remove-java.lang.String-) | Usuwa tag o określonej nazwie z kolekcji. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Zwraca indeks zerowy określonego klucza w kolekcji. |
| [contains(String name)](#contains-java.lang.String-) | Określa, czy kolekcja zawiera określoną nazwę. |
| [removeAt(int index)](#removeAt-int-) | Usuwa tag pod wskazanym indeksem. |
| [clear()](#clear--) | Usuwa wszystkie tagi z kolekcji. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Zwraca wartość tagu pod wskazanym indeksem. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Zwraca klucz tagu pod wskazanym indeksem. |
| [getNamesOfTags()](#getNamesOfTags--) | Zwraca nazwy tagów. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Zwraca lub ustawia parę klucz-wartość tagu. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Zwraca lub ustawia parę klucz-wartość tagu. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wszystkie elementy z kolekcji do podanej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo-bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
| [iterator()](#iterator--) | Zwraca enumerator iterujący po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator Java dla całej kolekcji. |
### size() {#size--}
```
public final int size()
```


Zwraca liczbę tagów w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```


Dodaje nowy tag do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa tagu. |
| value | java.lang.String | Wartość tagu. |

**Zwraca:**
int - Indeks dodanego tagu.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```


Usuwa tag o określonej nazwie z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa tagu do usunięcia. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```


Zwraca indeks zerowy określonego klucza w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa do wyszukania w kolekcji. |

**Zwraca:**
int - Indeks zerowy klucza, jeśli klucz zostanie znaleziony w kolekcji; w przeciwnym razie -1.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


Określa, czy kolekcja zawiera określoną nazwę.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Klucz do znalezienia. |

**Zwraca:**
boolean - True jeśli kolekcja zawiera tag z określonym kluczem; w przeciwnym razie false.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Usuwa tag pod wskazanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy tagu do usunięcia. |
### clear() {#clear--}
```
public final void clear()
```


Usuwa wszystkie tagi z kolekcji.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```


Zwraca wartość tagu pod wskazanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks tagu do zwrócenia. |

**Zwraca:**
java.lang.String - Wartość tagu.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```


Zwraca klucz tagu pod wskazanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks tagu do zwrócenia. |

**Zwraca:**
java.lang.String - Klucz tagu.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```


Zwraca nazwy tagów.

**Zwraca:**
java.lang.String[] - Nazwy tagów.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```


Zwraca lub ustawia parę klucz-wartość tagu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Klucz tagu. |

**Zwraca:**
java.lang.String - Wartość tagu.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```


Zwraca lub ustawia parę klucz-wartość tagu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Klucz tagu. |
| value | java.lang.String |  |
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopiuje wszystkie elementy z kolekcji do podanej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica do wypełnienia. |
| index | int | Pozycja początkowa w docelowej tablicy. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo-bezpieczny). Tylko do odczytu boolean.

**Zwraca:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Zwraca korzeń synchronizacji. Tylko do odczytu Object.

**Zwraca:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```


Zwraca enumerator iterujący po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```


Zwraca iterator Java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.