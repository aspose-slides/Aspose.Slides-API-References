---
title: PortionCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie van gedeelten voor.
type: docs
url: /nl/com.aspose.slides/portioncollection/
---
**Overerving:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

Stelt een collectie van gedeelten voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCount()](#getCount--) | Verkrijgt het aantal elementen dat daadwerkelijk in de collectie zit. |
| [isReadOnly()](#isReadOnly--) | Verkrijgt een waarde die aangeeft of de [IGenericCollection](../../com.aspose.slides/igenericcollection) alleen-lezen is. |
| [get_Item(int index)](#get-Item-int-) | Verkrijgt het element op de opgegeven index. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | Verkrijgt het element op de opgegeven index. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Voegt een Portion toe aan het einde van de collectie. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Bepaalt de index van een specifiek item in de List. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Voegt een Portion in de collectie op de opgegeven index in. |
| [clear()](#clear--) | Verwijdert alle elementen uit de collectie. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Bepaalt of de [IGenericCollection](../../com.aspose.slides/igenericcollection) een specifieke waarde bevat. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | Kopieert de elementen van de [IGenericCollection](../../com.aspose.slides/igenericcollection) naar een Array, beginnend bij een bepaalde Array-index. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Verwijdert het eerste voorkomen van een specifiek object uit de [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index van de collectie. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java iterator voor de volledige collectie. |
### getCount() {#getCount--}
```
public final int getCount()
```

Verkrijgt het aantal elementen dat daadwerkelijk in de collectie zit. Alleen-lezen int.

**Retourneert:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Verkrijgt een waarde die aangeeft of de [IGenericCollection](../../com.aspose.slides/igenericcollection) alleen-lezen is. Alleen-lezen boolean.

**Retourneert:**
boolean - true als de [IGenericCollection](../../com.aspose.slides/igenericcollection) alleen-lezen is; anders false.
### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```

Verkrijgt het element op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourneert:**
[IPortion](../../com.aspose.slides/iportion)
### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```

Verkrijgt het element op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```

Voegt een Portion toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | De Portion die aan het einde van de collectie moet worden toegevoegd. |
### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```

Bepaalt de index van een specifiek item in de List.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Het object om in de List te zoeken. |

**Retourneert:**
int - De index van item als het in de lijst is gevonden; anders -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```

Voegt een Portion in de collectie op de opgegeven index in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop de Portion moet worden ingevoegd. |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Het object om te zoeken in de [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retourneert:**
boolean - true als item wordt gevonden in de [IGenericCollection](../../com.aspose.slides/igenericcollection); anders false.
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

Kopieert de elementen van de [IGenericCollection](../../com.aspose.slides/igenericcollection) naar een Array, beginnend bij een bepaalde Array-index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | De eendimensionale Array die de bestemming is van de gekopieerde elementen van [IGenericCollection](../../com.aspose.slides/igenericcollection). De Array moet nulgebaseerde indexering hebben. |
| arrayIndex | int | De nulgebaseerde index in de array waarop het kopiëren begint. |
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

Verwijdert het eerste voorkomen van een specifiek object uit de [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Het object om te verwijderen uit de [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retourneert:**
boolean - true als item succesvol is verwijderd uit de [IGenericCollection](../../com.aspose.slides/igenericcollection); anders false. Deze methode geeft ook false terug als item niet wordt gevonden in de originele [IGenericCollection](../../com.aspose.slides/igenericcollection).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert het element op de opgegeven index van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het element dat moet worden verwijderd. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```

Retourneert een enumerator die door de collectie itereert.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```

Retourneert een java iterator voor de volledige collectie.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - Een java.util.Iterator voor de volledige collectie.