---
title: IControlPropertiesCollection
second_title: Aspose.Slides dla dokumentacji API Java
description: Kolekcja kontrolek ActiveX.
type: docs
url: /pl/com.aspose.slides/icontrolpropertiescollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

Kolekcja kontrolek ActiveX.
## Metody

| Metoda | Opis |
| --- | --- |
| [getCount()](#getCount--) | Zwraca liczbę właściwości w kolekcji. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Dodaje właściwość do kolekcji. |
| [remove(String name)](#remove-java.lang.String-) | Usuwa właściwość o określonej nazwie. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Zwraca lub ustawia właściwość. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Zwraca lub ustawia właściwość. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Zwraca liczbę właściwości w kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie właściwości. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Zwraca liczbę właściwości w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```


Dodaje właściwość do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa właściwości. |
| value | java.lang.String | Wartość właściwości. |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


Usuwa właściwość o określonej nazwie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa właściwości do usunięcia. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```


Zwraca lub ustawia właściwość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa właściwości. |

**Zwraca:**
java.lang.String - Property.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```


Zwraca lub ustawia właściwość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| name | java.lang.String | Nazwa właściwości. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```


Zwraca liczbę właściwości w kolekcji. Tylko do odczytu [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Zwraca:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```


Usuwa wszystkie właściwości.