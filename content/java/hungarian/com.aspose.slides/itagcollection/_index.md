---
title: ITagCollection
second_title: Aspose.Slides Java API Referencia
description: A címkék, a felhasználó által definiált karakterlánc párok gyűjteményét képviseli
type: docs
url: /hu/com.aspose.slides/itagcollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

A címkék (felhasználó által definiált karakterlánc párok) gyűjteményét reprezentálja
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Új címkét ad hozzá a gyűjteményhez. |
| [remove(String name)](#remove-java.lang.String-) | A megadott névvel rendelkező címkét eltávolítja a gyűjteményből. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Visszaadja a megadott kulcs nulla-alapú indexét a gyűjteményben. |
| [contains(String name)](#contains-java.lang.String-) | Meghatározza, hogy a gyűjtemény tartalmaz-e egy adott nevet. |
| [removeAt(int index)](#removeAt-int-) | A megadott indexű címkét eltávolítja. |
| [clear()](#clear--) | Az összes címkét eltávolítja a gyűjteményből. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Visszaadja egy címke értékét a megadott indexnél. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Visszaadja egy címke kulcsát a megadott indexnél. |
| [getNamesOfTags()](#getNamesOfTags--) | Visszaadja a címkék neveit. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Visszaad vagy beállít egy címke kulcs-érték párját. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Visszaad vagy beállít egy címke kulcs-érték párját. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```


Új címkét ad hozzá a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A címke neve. |
| value | java.lang.String | A címke értéke. |

**Visszatérési érték:**
int - A hozzáadott címke indexe.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


Eltávolítja a megadott névvel rendelkező címkét a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A törlendő címke neve. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```


Visszaadja a megadott kulcs nulla-alapú indexét a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A gyűjteményben keresendő név. |

**Visszatérési érték:**
int - A kulcs nulla-alapú indexe, ha a kulcs megtalálható a gyűjteményben; egyébként -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```


Megállapítja, hogy a gyűjtemény tartalmaz-e egy adott nevet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A keresett kulcs. |

**Visszatérési érték:**
boolean - True, ha a gyűjtemény tartalmaz egy megadott kulcsú címkét; egyébként false.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Eltávolítja a címkét a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A címke nulla-alapú indexe, amelyet el kell távolítani. |
### clear() {#clear--}
```
public abstract void clear()
```


Eltávolítja az összes címkét a gyűjteményből.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```


Visszaadja egy címke értékét a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A visszaadandó címke indexe. |

**Visszatérési érték:**
java.lang.String - Egy címke értéke.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```


Visszaadja egy címke kulcsát a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A visszaadandó címke indexe. |

**Visszatérési érték:**
java.lang.String - Egy címke kulcsa.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```


Visszaadja a címkék neveit.

**Visszatérési érték:**
java.lang.String[] - A címkék nevei.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```


Visszaad vagy beállít egy címke kulcs-érték párját.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | Egy címke kulcsa. |

**Visszatérési érték:**
java.lang.String - Egy címke értéke.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```


Visszaad vagy beállít egy címke kulcs-érték párját.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | Egy címke kulcsa. |
| value | java.lang.String |  |