---
title: TagCollection
second_title: Aspose.Slides pro Android přes Java API Reference
description: Představuje kolekci značek – uživatelsky definovaných dvojic řetězců
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

Představuje kolekci značek (uživatelsky definované páry řetězců)

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
| [size()](#size--) | Vrací počet značek ve sbírce. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Přidá novou značku do sbírky. |
| [remove(String name)](#remove-java.lang.String-) | Odstraní značku se zadaným názvem ze sbírky. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Vrací nulový index zadaného klíče ve sbírce. |
| [contains(String name)](#contains-java.lang.String-) | Určuje, zda sbírka obsahuje konkrétní název. |
| [removeAt(int index)](#removeAt-int-) | Odstraní značku na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny značky ze sbírky. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Vrací hodnotu značky na zadaném indexu. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Vrací klíč značky na zadaném indexu. |
| [getNamesOfTags()](#getNamesOfTags--) | Vrací názvy značek. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Vrací nebo nastavuje dvojici klíč-hodnota značky. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Vrací nebo nastavuje dvojici klíč-hodnota značky. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje všechny prvky ze sbírky do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu, která určuje, zda je přístup ke sbírce synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází sbírku. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou sbírku. |
### size() {#size--}
```
public final int size()
```

Vrací počet značek ve sbírce. Pouze pro čtení int.

**Vrací:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```

Přidá novou značku do sbírky.

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

Odstraní značku se zadaným názvem ze sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název značky k odebrání. |

### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

Vrací nulový index zadaného klíče ve sbírce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Název k vyhledání ve sbírce. |

**Vrací:**
int - Nulový index klíče, pokud byl ve sbírce nalezen; jinak -1.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

Určuje, zda sbírka obsahuje konkrétní název.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Klíč k vyhledání. |

**Vrací:**
boolean - True, pokud sbírka obsahuje značku se zadaným klíčem; jinak false.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odstraní značku na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index značky k odstranění. |

### clear() {#clear--}
```
public final void clear()
```

Odstraní všechny značky ze sbírky.

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

Vrací nebo nastavuje dvojici klíč-hodnota značky.

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

Vrací nebo nastavuje dvojici klíč-hodnota značky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| name | java.lang.String | Klíč značky. |
| value | java.lang.String |  |

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Zkopíruje všechny prvky ze sbírky do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Pole k naplnění. |
| index | int | Počáteční pozice v cílovém poli. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu, která určuje, zda je přístup ke sbírce synchronizován (vláknově bezpečný). Pouze pro čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací kořen synchronizace. Pouze pro čtení Object.

**Vrací:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Vrací enumerátor, který prochází sbírku.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - IGenericEnumerator, který lze použít k iteraci sbírky.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Vrací java iterátor pro celou sbírku.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - java.util.Iterator pro celou sbírku.