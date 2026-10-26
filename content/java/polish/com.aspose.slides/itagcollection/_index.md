---
title: ITagCollection
second_title: Aspose.Slides dla Java - odwołanie API
description: Reprezentuje kolekcję znaczników będących parami łańcuchów definiowanych przez użytkownika
type: docs
url: /pl/com.aspose.slides/itagcollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Reprezentuje kolekcję znaczników (pary łańcuchów zdefiniowane przez użytkownika)
## Metody

| Metoda | Opis |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Dodaje nowy znacznik do kolekcji. |
| [remove(String name)](#remove-java.lang.String-) | Usuwa znacznik o określonej nazwie z kolekcji. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Zwraca indeks zerowy określonego klucza w kolekcji. |
| [contains(String name)](#contains-java.lang.String-) | Określa, czy kolekcja zawiera określoną nazwę. |
| [removeAt(int index)](#removeAt-int-) | Usuwa znacznik pod podanym indeksem. |
| [clear()](#clear--) | Usuwa wszystkie znaczniki z kolekcji. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Zwraca wartość znacznika pod podanym indeksem. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Zwraca klucz znacznika pod podanym indeksem. |
| [getNamesOfTags()](#getNamesOfTags--) | Zwraca nazwy znaczników. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Zwraca lub ustawia parę klucz-wartość znacznika. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Zwraca lub ustawia parę klucz-wartość znacznika. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

Dodaje nowy znacznik do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa znacznika. |
| value | java.lang.String | Wartość znacznika. |

**Zwraca:**
int - Indeks dodanego znacznika.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

Usuwa znacznik o określonej nazwie z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa znacznika do usunięcia. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
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
public abstract boolean contains(String name)
```

Określa, czy kolekcja zawiera określoną nazwę.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Klucz do wyszukania. |

**Zwraca:**
boolean - true, jeśli kolekcja zawiera znacznik o podanym kluczu; w przeciwnym razie false.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa znacznik pod podanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy znacznika do usunięcia. |
### clear() {#clear--}
```
public abstract void clear()
```

Usuwa wszystkie znaczniki z kolekcji.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

Zwraca wartość znacznika pod podanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks znacznika do zwrócenia. |

**Zwraca:**
java.lang.String - Wartość znacznika.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

Zwraca klucz znacznika pod podanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks znacznika do zwrócenia. |

**Zwraca:**
java.lang.String - Klucz znacznika.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```

Zwraca nazwy znaczników.

**Zwraca:**
java.lang.String[] - Nazwy znaczników.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

Zwraca lub ustawia parę klucz-wartość znacznika.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Klucz znacznika. |

**Zwraca:**
java.lang.String - Wartość znacznika.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

Zwraca lub ustawia parę klucz-wartość znacznika.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Klucz znacznika. |
| value | java.lang.String |  |