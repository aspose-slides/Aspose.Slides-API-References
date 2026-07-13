---
title: BehaviorCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie van gedragseffecten voor.
type: docs
url: /nl/com.aspose.slides/behaviorcollection/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

Stelt een collectie van gedragseffecten voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCount()](#getCount--) | Retourneert het aantal gedragingen in een collectie. |
| [isReadOnly()](#isReadOnly--) | Haalt een waarde op die aangeeft of de [IGenericCollection](../../com.aspose.slides/igenericcollection) alleen-lezen is. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Voeg nieuw gedrag toe aan een collectie. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Bepaalt de index van een specifiek item in de List. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Voegt nieuw gedrag toe aan een collectie op de opgegeven index. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | Kopieert de elementen van de [IGenericCollection](../../com.aspose.slides/igenericcollection) naar een Array, beginnend op een specifieke Array-index. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Verwijdert gespecificeerd gedrag uit een collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert gedrag uit een collectie op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle gedragingen uit een collectie. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Bepaalt of de [IGenericCollection](../../com.aspose.slides/igenericcollection) een specifieke waarde bevat. |
| [get_Item(int index)](#get-Item-int-) | Retourneert een gedrag op de opgegeven index. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Stelt een gedrag in op de opgegeven index. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java iterator voor de gehele collectie. |
### getCount() {#getCount--}
```
public final int getCount()
```

Retourneert het aantal gedragingen in een collectie. Alleen-lezen int.

**Retourneert:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Haalt een waarde op die aangeeft of de [IGenericCollection](../../com.aspose.slides/igenericcollection) alleen-lezen is. Alleen-lezen boolean.

**Retourneert:**
boolean - true als de [IGenericCollection](../../com.aspose.slides/igenericcollection) alleen-lezen is; anders false.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```

Voeg nieuw gedrag toe aan een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Gedrag om toe te voegen. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```

Bepaalt de index van een specifiek item in de List.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Het object om te zoeken in de List. |

**Retourneert:**
int - De index van item als gevonden in de lijst; anders -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

Voegt nieuw gedrag toe aan een collectie op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index waar nieuw gedrag moet worden ingevoegd. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Gedrag om in te voegen. |

### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```

Kopieert de elementen van de [IGenericCollection](../../com.aspose.slides/igenericcollection) naar een Array, beginnend op een specifieke Array-index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | De eendimensionale Array die de bestemming is van de elementen die gekopieerd worden vanaf [IGenericCollection](../../com.aspose.slides/igenericcollection). De Array moet een nul-gebaseerde indexering hebben. |
| arrayIndex | int | De nul-gebaseerde index in de array waarop het kopiëren begint. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```

Verwijdert gespecificeerd gedrag uit een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Gedrag om te verwijderen. |

**Retourneert:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert gedrag uit een collectie op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een gedrag om te verwijderen. |

### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle gedragingen uit een collectie.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```

Bepaalt of de [IGenericCollection](../../com.aspose.slides/igenericcollection) een specifieke waarde bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Het object om te zoeken in de [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retourneert:**
boolean - true als item wordt gevonden in de [IGenericCollection](../../com.aspose.slides/igenericcollection); anders false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```

Retourneert een gedrag op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een gedrag om te retourneren. |

**Retourneert:**
[IBehavior](../../com.aspose.slides/ibehavior) - Animatiegedrag.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

Stelt een gedrag in op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een gedrag om te retourneren. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```

Retourneert een enumerator die door de collectie iterereert.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```

Retourneert een java iterator voor de gehele collectie.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - Een java.util.Iterator voor de gehele collectie.