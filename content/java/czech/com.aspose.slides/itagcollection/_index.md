---
title: ITagCollection
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje kolekci štítků, uživatelem definovaných dvojic řetězců
type: docs
url: /cs/com.aspose.slides/itagcollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Reprezentuje kolekci štítků (uživatelem definovaných dvojic řetězců)
## Metody

| Metoda | Popis |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Adds a new tag to collection. |
| [remove(String name)](#remove-java.lang.String-) | Removes the tag with a specified name from the collection. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Returns the zero-based index of the specified key in the collection. |
| [contains(String name)](#contains-java.lang.String-) | Determines whether the collection contains a specific name. |
| [removeAt(int index)](#removeAt-int-) | Removes the tag at the specified index. |
| [clear()](#clear--) | Removes all tags from the collection. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Returns value of a tag at the specified index. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Returns key of a tag at the specified index. |
| [getNamesOfTags()](#getNamesOfTags--) | Returns names of tags. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Returns or sets a key and a value pair of a tag. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Returns or sets a key and a value pair of a tag. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```


Přidá nový štítek do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název štítku. |
| value | java.lang.String | Hodnota štítku. |

**Vrací:**
int - Index přidaného štítku.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


Odstraní štítek se zadaným názvem z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název štítku k odstranění. |

### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```


Vrací nulový index zadaného klíče v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název k vyhledání v kolekci. |

**Vrací:**
int - Nulový index klíče, pokud je klíč v kolekci nalezen; jinak -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```


Určuje, zda kolekce obsahuje konkrétní název.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Klíč k vyhledání. |

**Vrací:**
boolean - True if the collection contains an tag with the specified key; otherwise, false.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Odstraní štítek na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index štítku k odstranění. |

### clear() {#clear--}
```
public abstract void clear()
```


Odstraní všechny štítky z kolekce.

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```


Vrací hodnotu štítku na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index štítku k vrácení. |

**Vrací:**
java.lang.String - Hodnota štítku.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```


Vrací klíč štítku na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index štítku k vrácení. |

**Vrací:**
java.lang.String - Klíč štítku.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```


Vrací názvy štítků.

**Vrací:**
java.lang.String[] - Názvy štítků.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```


Vrací nebo nastavuje klíč a hodnotu páru štítku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Klíč štítku. |

**Vrací:**
java.lang.String - Hodnota štítku.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```


Vrací nebo nastavuje klíč a hodnotu páru štítku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Klíč štítku. |
| value | java.lang.String |  |