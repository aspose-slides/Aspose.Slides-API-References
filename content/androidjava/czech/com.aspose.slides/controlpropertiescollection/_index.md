---
title: ControlPropertiesCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Kolekce vlastností AcitveX.
type: docs
url: /cs/com.aspose.slides/controlpropertiescollection/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

Kolekce vlastností AcitveX.
## Metody

| Metoda | Popis |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Adds a property to the collection. |
| [remove(String name)](#remove-java.lang.String-) | Removes a property with the specified name. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Returns or sets property. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Returns or sets property. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Returns the collection of properties names. |
| [clear()](#clear--) | Removes all properties. |
| [getCount()](#getCount--) | Returns a number of properties in the collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```


Přidá vlastnost do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastnosti. |
| value | java.lang.String | Hodnota vlastnosti. |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```


Odstraní vlastnost se zadaným názvem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastnosti k odstranění. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```


Vrací nebo nastavuje vlastnost.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastnosti. |

**Návratová hodnota:**
java.lang.String - Vlastnost.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```


Vrací nebo nastavuje vlastnost.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název vlastnosti. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```


Vrací kolekci názvů vlastností. Pouze pro čtení [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Návratová hodnota:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public final void clear()
```


Odstraní všechny vlastnosti.

### getCount() {#getCount--}
```
public final int getCount()
```


Vrací počet vlastností v kolekci. Pouze pro čtení int.

**Návratová hodnota:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```


Vrací enumerátor, který prochází kolekcí.

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```


Vrací iterátor java pro celou kolekci.

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.