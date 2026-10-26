---
title: PortionCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een verzameling van Portion voor.
type: docs
url: /nl/com.aspose.slides/portioncollection/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

Stelt een verzameling van Portion voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCount()](#getCount--) | Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. |
| [isReadOnly()](#isReadOnly--) | Haalt een waarde op die aangeeft of de [IGenericCollection](../../com.aspose.slides/igenericcollection) alleen-lezen is. |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | Haalt het element op op de opgegeven index. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Voegt een Portion toe aan het einde van de collectie. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Bepaalt de index van een specifiek item in de List. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Voegt een Portion in de collectie in op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle elementen uit de collectie. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Bepaalt of de [IGenericCollection](../../com.aspose.slides/igenericcollection) een specifieke waarde bevat. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | Kopieert de elementen van de [IGenericCollection](../../com.aspose.slides/igenericcollection) naar een Array, beginnend bij een bepaalde Array-index. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Verwijdert de eerste voorkoming van een specifiek object uit de [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index van de collectie. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java iterator voor de volledige collectie. |
### getCount() {#getCount--}
```
public final int getCount()
```

Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. Alleen-lezen int.

**Retour:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Haalt een waarde op die aangeeft of de [IGenericCollection](../../com.aspose.slides/igenericcollection) alleen-lezen is. Alleen-lezen boolean.

**Retour:**
boolean - true if the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only; otherwise, false.
### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```

Haalt het element op op de opgegeven index.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IPortion](../../com.aspose.slides/iportion)
### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```

Haalt het element op op de opgegeven index.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |

### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```

Voegt een Portion toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | De Portion die aan het einde van de collectie moet worden toegevoegd. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```

Bepaalt de index van een specifiek item in de List.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Het object dat moet worden gevonden in de List. |

**Retour:**
int - De index van het item als het wordt gevonden in de lijst; anders -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```

Voegt een Portion in de collectie in op de opgegeven index.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index waarop de Portion moet worden ingevoegd. |
| value | [IPortion](../../com.aspose.slides/iportion) | De in te voegen Portion. |

### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle elementen uit de collectie.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```

Bepaalt of de [IGenericCollection](../../com.aspose.slides/igenericcollection) een specifieke waarde bevat.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Het object dat moet worden gevonden in de [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retour:**
boolean - true als het item wordt gevonden in de [IGenericCollection](../../com.aspose.slides/igenericcollection); anders false.
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

Kopieert de elementen van de [IGenericCollection](../../com.aspose.slides/igenericcollection) naar een Array, beginnend bij een bepaalde Array-index.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | De één-dimensionale Array die de bestemming is van de elementen gekopieerd van [IGenericCollection](../../com.aspose.slides/igenericcollection). De Array moet nul-gebaseerde indexering hebben. |
| arrayIndex | int | De nul-gebaseerde index in de array waarop het kopiëren begint. |

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

Verwijdert de eerste voorkoming van een specifiek object uit de [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Het object dat moet worden verwijderd uit de [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retour:**
boolean - true als het item succesvol is verwijderd uit de [IGenericCollection](../../com.aspose.slides/igenericcollection); anders false. Deze methode retourneert ook false als het item niet wordt gevonden in de oorspronkelijke [IGenericCollection](../../com.aspose.slides/igenericcollection).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert het element op de opgegeven index van de collectie.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index van het te verwijderen element. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```

Retourneert een enumerator die door de collectie iterereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```

Retourneert een java iterator voor de volledige collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - An java.util.Iterator for the entire collection.