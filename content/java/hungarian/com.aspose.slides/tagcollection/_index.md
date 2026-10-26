---
title: TagCollection
second_title: Aspose.Slides Java API hivatkozás
description: A címkék (felhasználó által definiált karakterlánc párok) gyűjteményét képviseli
type: docs
url: /hu/com.aspose.slides/tagcollection/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

A címkék (felhasználó által definiált karakterlánc párok) gyűjteményét képviseli

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
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [size()](#size--) | Visszaadja a címkék számát a gyűjteményben. Csak olvasható int. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Új címkét ad a gyűjteményhez. |
| [remove(String name)](#remove-java.lang.String-) | Eltávolítja a megadott névű címkét a gyűjteményből. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Visszaadja a megadott kulcs nulla alapú indexét a gyűjteményben. |
| [contains(String name)](#contains-java.lang.String-) | Megállapítja, hogy a gyűjtemény tartalmaz-e egy adott nevet. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a címkét a megadott indexen. |
| [clear()](#clear--) | Eltávolítja az összes címkét a gyűjteményből. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Visszaadja egy címke értékét a megadott indexen. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Visszaadja egy címke kulcsát a megadott indexen. |
| [getNamesOfTags()](#getNamesOfTags--) | Visszaadja a címkék neveit. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Visszaad vagy beállít egy kulcs-érték párt egy címkéhez. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Visszaad vagy beállít egy kulcs-érték párt egy címkéhez. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Átmásolja az összes elemet a gyűjteményből a megadott tömbbe. |
| [isSynchronized()](#isSynchronized--) | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). Csak olvasható boolean. |
| [getSyncRoot()](#getSyncRoot--) | Visszaad egy szinkronizációs gyökér elemet. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort az egész gyűjteményhez. |
### size() {#size--}
```
public final int size()
```

Visszaadja a címkék számát a gyűjteményben. Csak olvasható int.

**Visszatér:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```

Új címkét ad a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A címke neve. |
| value | java.lang.String | A címke értéke. |

**Visszatér:**
int - A hozzáadott címke indexe.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Eltávolítja a megadott névű címkét a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A törlendő címke neve. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

Visszaadja a megadott kulcs nulla alapú indexét a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A keresett név a gyűjteményben. |

**Visszatér:**
int - A kulcs nulla alapú indexe, ha a kulcs megtalálható a gyűjteményben; egyébként -1.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

Megállapítja, hogy a gyűjtemény tartalmaz-e egy adott nevet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A keresett kulcs. |

**Visszatér:**
boolean - Igaz, ha a gyűjtemény tartalmaz egy megadott kulccsal rendelkező címkét; egyébként hamis.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja a címkét a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A törlendő címke nulla alapú indexe. |
### clear() {#clear--}
```
public final void clear()
```

Eltávolítja az összes címkét a gyűjteményből.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

Visszaadja egy címke értékét a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A visszaadandó címke indexe. |

**Visszatér:**
java.lang.String - A címke értéke.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```

Visszaadja egy címke kulcsát a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A visszaadandó címke indexe. |

**Visszatér:**
java.lang.String - A címke kulcsa.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

Visszaadja a címkék neveit.

**Visszatér:**
java.lang.String[] - A címkék nevei.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Visszaad vagy beállít egy kulcs-érték párt egy címkéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A címke kulcsa. |

**Visszatér:**
java.lang.String - A címke értéke.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Visszaad vagy beállít egy kulcs-érték párt egy címkéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | A címke kulcsa. |
| value | java.lang.String |  |
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Átmásolja az összes elemet a gyűjteményből a megadott tömbbe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | A kitöltendő tömb. |
| index | int | A kiinduló pozíció a cél tömbben. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált-e (szálbiztos). Csak olvasható boolean.

**Visszatér:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Visszaad egy szinkronizációs gyökér elemet. Csak olvasható Object.

**Visszatér:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Visszaad egy java iterátort az egész gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Egy java.util.Iterator az egész gyűjteményhez.