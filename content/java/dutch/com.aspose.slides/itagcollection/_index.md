---
title: ITagCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt de verzameling tags voor met gebruikergedefinieerde paren van strings
type: docs
url: /nl/com.aspose.slides/itagcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Stelt de verzameling tags voor (gebruikersgedefinieerde paar strings)
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Voegt een nieuwe tag toe aan de verzameling. |
| [remove(String name)](#remove-java.lang.String-) | Verwijdert de tag met een opgegeven naam uit de verzameling. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Retourneert de nulgebaseerde index van de opgegeven sleutel in de verzameling. |
| [contains(String name)](#contains-java.lang.String-) | Bepaalt of de verzameling een specifieke naam bevat. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert de tag op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle tags uit de verzameling. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Retourneert de waarde van een tag op de opgegeven index. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Retourneert de sleutel van een tag op de opgegeven index. |
| [getNamesOfTags()](#getNamesOfTags--) | Retourneert namen van tags. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Retourneert of stelt een sleutel- en waardepaar van een tag in. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Retourneert of stelt een sleutel- en waardepaar van een tag in. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

Voegt een nieuwe tag toe aan de verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | De naam van de tag. |
| value | java.lang.String | De waarde van de tag. |

**Retour:**
int - De index van de toegevoegde tag.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

Verwijdert de tag met een opgegeven naam uit de verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | De naam van de te verwijderen tag. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```

Retourneert de nulgebaseerde index van de opgegeven sleutel in de verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | De naam die in de verzameling moet worden opgezocht. |

**Retour:**
int - De nulgebaseerde index van de sleutel, of -1 als de sleutel niet wordt gevonden.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

Bepaalt of de verzameling een specifieke naam bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | De sleutel die moet worden opgezocht. |

**Retour:**
boolean - Waar als de verzameling een tag met de opgegeven sleutel bevat; anders, onwaar.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert de tag op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van de te verwijderen tag. |
### clear() {#clear--}
```
public abstract void clear()
```

Verwijdert alle tags uit de verzameling.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

Retourneert de waarde van een tag op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een tag die moet worden geretourneerd. |

**Retour:**
java.lang.String - Waarde van een tag.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

Retourneert de sleutel van een tag op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een tag die moet worden geretourneerd. |

**Retour:**
java.lang.String - Sleutel van een tag.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```

Retourneert namen van tags.

**Retour:**
java.lang.String[] - Namen van tags.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

Retourneert of stelt een sleutel- en waardepaar van een tag in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Sleutel van een tag. |

**Retour:**
java.lang.String - Waarde van een tag.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

Retourneert of stelt een sleutel- en waardepair van een tag in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Sleutel van een tag. |
| value | java.lang.String |  |