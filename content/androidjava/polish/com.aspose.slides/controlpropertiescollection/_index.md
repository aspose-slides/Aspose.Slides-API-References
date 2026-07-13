---
title: ControlPropertiesCollection
second_title: Aspose.Slides dla Androida – odniesienie do API Javy
description: Kolekcja właściwości AcitveX.
type: docs
url: /pl/com.aspose.slides/controlpropertiescollection/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

Kolekcja właściwości AcitveX.
## Metody

| Metoda | Opis |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Dodaje właściwość do kolekcji. |
| [remove(String name)](#remove-java.lang.String-) | Usuwa właściwość o określonej nazwie. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Zwraca lub ustawia właściwość. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Zwraca lub ustawia właściwość. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Zwraca kolekcję nazw właściwości. |
| [clear()](#clear--) | Usuwa wszystkie właściwości. |
| [getCount()](#getCount--) | Zwraca liczbę właściwości w kolekcji. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator java dla całej kolekcji. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

Dodaje właściwość do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa właściwości. |
| value | java.lang.String | Wartość właściwości. |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Usuwa właściwość o określonej nazwie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa właściwości do usunięcia. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Zwraca lub ustawia właściwość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa właściwości. |

**Zwraca:**
java.lang.String - Właściwość.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Zwraca lub ustawia właściwość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa właściwości. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

Zwraca kolekcję nazw właściwości. Tylko do odczytu [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Zwraca:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public final void clear()
```

Usuwa wszystkie właściwości.

### getCount() {#getCount--}
```
public final int getCount()
```

Zwraca liczbę właściwości w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - IGenericEnumerator, który może być użyty do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Zwraca iterator java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Iterator java.util dla całej kolekcji.