---
title: ITagCollection
second_title: Aspose.Slides pro Android prostřednictvím referenční příručky Java API
description: Reprezentuje kolekci značek - uživatelem definovaných dvojic řetězců
type: docs
url: /cs/com.aspose.slides/itagcollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Reprezentuje kolekci značek (uživatelem definované dvojice řetězců)
## Metody

| Metoda | Popis |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Přidá nový tag do kolekce. |
| [remove(String name)](#remove-java.lang.String-) | Odstraní značku s určeným názvem z kolekce. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Vrací nulový index zadaného klíče v kolekci. |
| [contains(String name)](#contains-java.lang.String-) | Určuje, zda kolekce obsahuje konkrétní název. |
| [removeAt(int index)](#removeAt-int-) | Odstraní značku na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny značky z kolekce. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Vrací hodnotu značky na zadaném indexu. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Vrací klíč značky na zadaném indexu. |
| [getNamesOfTags()](#getNamesOfTags--) | Vrací názvy značek. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Vrací nebo nastavuje dvojici klíč-hodnota značky. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Vrací nebo nastavuje dvojici klíč-hodnota značky. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

Přidá nový tag do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název značky. |
| value | java.lang.String | Hodnota značky. |

**Vrací:**
int – Index přidané značky.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

Odstraní značku s určeným názvem z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název značky, kterou odstranit. |
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
int – Nulový index klíče, pokud je klíč v kolekci nalezen; jinak -1.
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
boolean – True, pokud kolekce obsahuje značku se zadaným klíčem; jinak false.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraní značku na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index značky, kterou odstranit. |
### clear() {#clear--}
```
public abstract void clear()
```

Odstraní všechny značky z kolekce.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

Vrací hodnotu značky na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index značky, která se má vrátit. |

**Vrací:**
java.lang.String – Hodnota značky.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

Vrací klíč značky na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index značky, která se má vrátit. |

**Vrací:**
java.lang.String – Klíč značky.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```

Vrací názvy značek.

**Vrací:**
java.lang.String[] – Názvy značek.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

Vrací nebo nastavuje dvojici klíč-hodnota značky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Klíč značky. |

**Vrací:**
java.lang.String – Hodnota značky.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

Vrací nebo nastavuje dvojici klíč-hodnota značky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Klíč značky. |
| value | java.lang.String |  |