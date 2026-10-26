---
title: TagCollection
second_title: Aspose.Slides pro Java API Reference
description: Representuje kolekci značek uživatelem definovaných dvojic řetězců
type: docs
url: /cs/com.aspose.slides/tagcollection/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

Reprezentuje kolekci značek (uživatelem definovaných dvojic řetězců)

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
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Vrací počet značek v kolekci. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Přidá novou značku do kolekce. |
| [remove(String name)](#remove-java.lang.String-) | Odstraní značku se zadaným názvem z kolekce. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Vrací nulově založený index zadaného klíče v kolekci. |
| [contains(String name)](#contains-java.lang.String-) | Určuje, zda kolekce obsahuje konkrétní název. |
| [removeAt(int index)](#removeAt-int-) | Odstraní značku na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny značky z kolekce. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Vrací hodnotu značky na zadaném indexu. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Vrací klíč značky na zadaném indexu. |
| [getNamesOfTags()](#getNamesOfTags--) | Vrací názvy značek. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Vrací nebo nastavuje dvojici klíč a hodnota značky. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Vrací nebo nastavuje dvojici klíč a hodnota značky. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje všechny prvky z kolekce do určeného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu určující, zda je přístup ke kolekci synchronizován (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Vrací synchronizační kořen. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekci. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
### size() {#size--}
```
public final int size()
```

Vrací počet značek v kolekci. int pouze pro čtení.

**Vrací:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```

Přidá novou značku do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název značky. |
| value | java.lang.String | Hodnota značky. |

**Vrací:**
int - Index přidané značky.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Odstraní značku se zadaným názvem z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název značky k odstranění. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

Vrací nulově založený index zadaného klíče v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název k vyhledání v kolekci. |

**Vrací:**
int - Nulově založený index klíče, pokud je klíč v kolekci nalezen; jinak -1.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
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
public final void removeAt(int index)
```

Odstraní značku na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulově založený index značky k odstranění. |
### clear() {#clear--}
```
public final void clear()
```

Odstraní všechny značky z kolekce.

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

Vrací hodnotu značky na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index značky k vrácení. |

**Vrací:**
java.lang.String - Hodnota značky.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```

Vrací klíč značky na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index značky k vrácení. |

**Vrací:**
java.lang.String - Klíč značky.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

Vrací názvy značek.

**Vrací:**
java.lang.String[] - Názvy značek.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Vrací nebo nastavuje dvojici klíč a hodnota značky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Klíč značky. |

**Vrací:**
java.lang.String - Hodnota značky.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Vrací nebo nastavuje dvojici klíč a hodnota značky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Klíč značky. |
| value | java.lang.String |  |
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Zkopíruje všechny prvky z kolekce do určeného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Pole k naplnění. |
| index | int | Počáteční pozice v cílovém poli. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu určující, zda je přístup ke kolekci synchronizován (thread-safe). boolean pouze pro čtení.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací synchronizační kořen. Objekt pouze pro čtení.

**Vrací:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Vrací enumerátor, který prochází kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - java.util.Iterator pro celou kolekci.