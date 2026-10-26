---
title: TagCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt de collectie van tags voor, een gebruikersgedefinieerde set van stringparen
type: docs
url: /nl/com.aspose.slides/tagcollection/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

Stelt de collectie van tags voor (gebruikersgedefinieerde paren van strings)

--------------------

> ```
> Het volgende voorbeeld laat zien hoe u een tag toevoegt aan een PowerPoint-presentatie.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ITagCollection tags = pres.getCustomData().getTags();
>      pres.getCustomData().getTags().add("MyTag", "My Tag Value");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [size()](#size--) | Retourneert een aantal tags in de collectie. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Voegt een nieuwe tag toe aan de collectie. |
| [remove(String name)](#remove-java.lang.String-) | Verwijdert de tag met een opgegeven naam uit de collectie. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Retourneert de nulgebaseerde index van de opgegeven sleutel in de collectie. |
| [contains(String name)](#contains-java.lang.String-) | Bepaalt of de collectie een specifieke naam bevat. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert de tag op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle tags uit de collectie. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Retourneert de waarde van een tag op de opgegeven index. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Retourneert de sleutel van een tag op de opgegeven index. |
| [getNamesOfTags()](#getNamesOfTags--) | Retourneert namen van tags. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Retourneert of stelt een sleutel- en waardepaar van een tag in. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Retourneert of stelt een sleutel- en waardepaar van een tag in. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen uit de collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of toegang tot de collectie gesynchroniseerd (thread-safe) is. |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een Java-iterator voor de volledige collectie. |
### size() {#size--}
```
public final int size()
```


Retourneert een aantal tags in de collectie. Alleen-lezen int.

**Retourneert:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```


Voegt een nieuwe tag toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | De naam van de tag. |
| value | java.lang.String | De waarde van de tag. |

**Retourneert:**
int - De index van de toegevoegde tag.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```


Verwijdert de tag met een opgegeven naam uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | De naam van de te verwijderen tag. |

### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```


Retourneert de nulgebaseerde index van de opgegeven sleutel in de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | De naam om in de collectie te zoeken. |

**Retourneert:**
int - De nulgebaseerde index van de sleutel, indien gevonden; anders -1.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


Bepaalt of de collectie een specifieke naam bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | De sleutel om te zoeken. |

**Retourneert:**
boolean - True als de collectie een tag met de opgegeven sleutel bevat; anders false.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Verwijdert de tag op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van de te verwijderen tag. |

### clear() {#clear--}
```
public final void clear()
```


Verwijdert alle tags uit de collectie.

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```


Retourneert de waarde van een tag op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een tag om te retourneren. |

**Retourneert:**
java.lang.String - Waarde van een tag.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```


Retourneert de sleutel van een tag op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een tag om te retourneren. |

**Retourneert:**
java.lang.String - Sleutel van een tag.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```


Retourneert namen van tags.

**Retourneert:**
java.lang.String[] - Namen van tags.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```


Retourneert of stelt een sleutel- en waardepaar van een tag in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Sleutel van een tag. |

**Retourneert:**
java.lang.String - Waarde van een tag.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```


Retourneert of stelt een sleutel- en waardepaar van een tag in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Sleutel van een tag. |
| value | java.lang.String |  |

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopieert alle elementen uit de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array om te vullen. |
| index | int | Startpositie in doelarray. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Retourneert een waarde die aangeeft of toegang tot de collectie gesynchroniseerd (thread-safe) is. Alleen-lezen boolean.

**Retourneert:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Retourneert een synchronisatiewortel. Alleen-lezen Object.

**Retourneert:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```


Retourneert een enumerator die door de collectie iterereert.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```


Retourneert een Java-iterator voor de volledige collectie.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Een java.util.Iterator voor de volledige collectie.