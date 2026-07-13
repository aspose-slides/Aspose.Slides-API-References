---
title: ITagCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt de collectie tags voor, door de gebruiker gedefinieerde stringparen
type: docs
url: /nl/com.aspose.slides/itagcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Stelt de collectie tags (door de gebruiker gedefinieerde stringparen) voor.
## Methoden

| Method | Description |
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


Voegt een nieuwe tag toe aan de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | De naam van de tag. |
| value | java.lang.String | De waarde van de tag. |

**Returns:**
int - De index van de toegevoegde tag.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


Verwijdert de tag met een opgegeven naam uit de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | De naam van de te verwijderen tag. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```


Retourneert de nulgebaseerde index van de opgegeven sleutel in de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | De naam om in de collectie te zoeken. |

**Returns:**
int - De nulgebaseerde index van de sleutel, als de sleutel wordt gevonden in de collectie; anders -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```


Bepaalt of de collectie een specifieke naam bevat.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | De sleutel om te zoeken. |

**Returns:**
boolean - True als de collectie een tag met de opgegeven sleutel bevat; anders false.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Verwijdert de tag op de opgegeven index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nulgebaseerde index van de te verwijderen tag. |
### clear() {#clear--}
```
public abstract void clear()
```


Verwijdert alle tags uit de collectie.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```


Retourneert de waarde van een tag op de opgegeven index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index van een tag om te retourneren. |

**Returns:**
java.lang.String - Waarde van een tag.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```


Retourneert de sleutel van een tag op de opgegeven index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index van een tag om te retourneren. |

**Returns:**
java.lang.String - Sleutel van een tag.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```


Retourneert de namen van tags.

**Returns:**
java.lang.String[] - Namen van tags.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```


Retourneert of stelt een sleutel-waarde-paar van een tag in.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Sleutel van een tag. |

**Returns:**
java.lang.String - Waarde van een tag.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```


Retourneert of stelt een sleutel-waarde-paar van een tag in.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Sleutel van een tag. |
| value | java.lang.String |  |