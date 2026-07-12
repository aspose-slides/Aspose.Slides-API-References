---
title: ITagCollection
second_title: Aspose.Slides Androidra a Java API hivatkozás alapján
description: A címkék felhasználó által definiált karakterlánc párokkal rendelkező gyűjteményét képviseli
type: docs
url: /hu/com.aspose.slides/itagcollection/
---
**Az összes megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

A címkék (felhasználó által meghatározott karakterlánc párok) gyűjteményét képviseli
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Új címkét ad a gyűjteményhez. |
| [remove(String name)](#remove-java.lang.String-) | Eltávolítja a megadott névvel rendelkező címkét a gyűjteményből. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Visszaadja a megadott kulcs nullaalapú indexét a gyűjteményben. |
| [contains(String name)](#contains-java.lang.String-) | Megállapítja, hogy a gyűjtemény tartalmaz-e egy adott nevet. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a címkét a megadott indexen. |
| [clear()](#clear--) | Eltávolítja az összes címkét a gyűjteményből. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Visszaadja egy címke értékét a megadott indexen. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Visszaadja egy címke kulcsát a megadott indexen. |
| [getNamesOfTags()](#getNamesOfTags--) | Visszaadja a címkék neveit. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Visszaad vagy beállít egy címke kulcs-érték párját. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Visszaad vagy beállít egy címke kulcs-érték párját. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

Új címkét ad a gyűjteményhez.

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

Visszaadja a megadott kulcs nullaalapú indexét a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A keresendő név a gyűjteményben. |

**Visszatérési érték:**
int - A kulcs nullaalapú indexe, ha a kulcs megtalálható a gyűjteményben; egyébként -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

Megállapítja, hogy a gyűjtemény tartalmaz-e egy adott nevet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A keresendő kulcs. |

**Visszatérési érték:**
boolean - Igaz, ha a gyűjtemény tartalmaz egy címkét a megadott kulccsal; egyébként hamis.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a címkét a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A törlendő címke nullaalapú indexe. |
### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes címkét a gyűjteményből.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

Visszaadja egy címke értékét a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A visszaadandó címke indexe. |

**Visszatérési érték:**
java.lang.String - A címke értéke.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

Visszaadja egy címke kulcsát a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A visszaadandó címke indexe. |

**Visszatérési érték:**
java.lang.String - A címke kulcsa.
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
| name | java.lang.String | A címke kulcsa. |

**Visszatérési érték:**
java.lang.String - A címke értéke.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

Visszaad vagy beállít egy címke kulcs-érték párját.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A címke kulcsa. |
| value | java.lang.String |  |