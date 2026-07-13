---
title: ITagCollection
second_title: Aspose.Slides dla Androida przy użyciu Java API
description: Reprezentuje kolekcję tagów będących parami ciągów znaków definiowanych przez użytkownika
type: docs
url: /pl/com.aspose.slides/itagcollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Reprezentuje kolekcję tagów (pary ciągów znaków definiowane przez użytkownika)
## Metody

| Metoda | Opis |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Dodaje nowy tag do kolekcji. |
| [remove(String name)](#remove-java.lang.String-) | Usuwa tag o podanej nazwie z kolekcji. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Zwraca indeks zerowy określonego klucza w kolekcji. |
| [contains(String name)](#contains-java.lang.String-) | Określa, czy kolekcja zawiera określoną nazwę. |
| [removeAt(int index)](#removeAt-int-) | Usuwa tag o podanym indeksie. |
| [clear()](#clear--) | Usuwa wszystkie tagi z kolekcji. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Zwraca wartość tagu o podanym indeksie. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Zwraca klucz tagu o podanym indeksie. |
| [getNamesOfTags()](#getNamesOfTags--) | Zwraca nazwy tagów. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Zwraca lub ustawia parę klucz-wartość tagu. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Zwraca lub ustawia parę klucz-wartość tagu. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
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
public abstract void remove(String name)
```


Usuwa tag o podanej nazwie z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa tagu do usunięcia. |
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
boolean - True jeśli kolekcja zawiera tag o podanym kluczu; w przeciwnym razie false.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Usuwa tag o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy tagu do usunięcia. |
### clear() {#clear--}
```
public abstract void clear()
```


Usuwa wszystkie tagi z kolekcji.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```


Zwraca wartość tagu o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks tagu do zwrócenia. |

**Zwraca:**
java.lang.String - Wartość tagu.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```


Zwraca klucz tagu o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks tagu do zwrócenia. |

**Zwraca:**
java.lang.String - Klucz tagu.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```


Zwraca nazwy tagów.

**Zwraca:**
java.lang.String[] - Nazwy tagów.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
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
public abstract void set_Item(String name, String value)
```


Zwraca lub ustawia parę klucz-wartość tagu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Klucz tagu. |
| value | java.lang.String |  |