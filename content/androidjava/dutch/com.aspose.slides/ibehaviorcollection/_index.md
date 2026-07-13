---
title: IBehaviorCollection
second_title: Aspose.Slides voor Android via Java API Referentie
description: Stelt een collectie van gedragseffecten voor.
type: docs
url: /nl/com.aspose.slides/ibehaviorcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

Stelt een collectie van gedragseffecten voor.
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert een gedrag op de opgegeven index. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Retourneert een gedrag op de opgegeven index. |
| [getCount()](#getCount--) | Retourneert het aantal gedragingen in een collectie. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Voegt nieuw gedrag toe aan een collectie. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Bepaalt de index van een specifiek item in de lijst. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Voegt nieuw gedrag in een collectie in op de opgegeven index. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Verwijdert gespecificeerd gedrag uit een collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert gedrag uit een collectie op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle gedragingen uit een collectie. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Bepaalt of de [IGenericCollection](../../com.aspose.slides/igenericcollection) een specifieke waarde bevat. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```

Retourneert een gedrag op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een gedrag om te retourneren. |

**Returns:**
[IBehavior](../../com.aspose.slides/ibehavior) - Animatiegedrag.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```

Retourneert een gedrag op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een gedrag om te retourneren. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Retourneert het aantal gedragingen in een collectie. Alleen-lezen int.

**Returns:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

Voegt nieuw gedrag toe aan een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Gedrag om toe te voegen. |
### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```

Bepaalt de index van een specifiek item in de lijst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Het object om te zoeken in de lijst. |

**Returns:**
int - De index van het item als het gevonden wordt in de lijst; anders -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

Voegt nieuw gedrag in een collectie in op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index waar nieuw gedrag moet worden ingevoegd. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Gedrag om in te voegen. |
### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

Verwijdert gespecificeerd gedrag uit een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Gedrag om te verwijderen. |

**Returns:**
boolean - True als een gedrag succesvol verwijderd is boolean
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert gedrag uit een collectie op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een gedrag om te verwijderen. |
### clear() {#clear--}
```
public abstract void clear()
```

Verwijdert alle gedragingen uit een collectie.
### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```

Bepaalt of de [IGenericCollection](../../com.aspose.slides/igenericcollection) een specifieke waarde bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Het object om te zoeken in de [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returns:**
boolean - true als het item wordt gevonden in de [IGenericCollection](../../com.aspose.slides/igenericcollection); anders false.