---
title: ISequenceCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een collectie van interactieve sequensen voor.
type: docs
url: /nl/com.aspose.slides/isequencecollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

Stelt een collectie van interactieve sequensen voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCount()](#getCount--) | Retourneert het aantal elementen in een collectie Alleen-lezen int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Voeg een nieuwe interactieve sequensie toe. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Verwijdert de opgegeven sequensie uit een collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert sequensie op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle sequensen uit een collectie. |
| [get_Item(int index)](#get-Item-int-) | Retourneert een sequense op de opgegeven index. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Retourneert het aantal elementen in een collectie Alleen-lezen int.

**Retourneert:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```


Voeg een nieuwe interactieve sequensie toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | Shape object [IShape](../../com.aspose.slides/ishape) |

**Retourneert:**
[ISequence](../../com.aspose.slides/isequence) - Nieuwe sequentie [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```


Verwijdert de opgegeven sequensie uit een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Sequentie om te verwijderen. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Verwijdert sequensie op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van element in de collectie int |

### clear() {#clear--}
```
public abstract void clear()
```


Verwijdert alle sequensen uit een collectie.

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```


Retourneert een sequense op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van element. |

**Retourneert:**
[ISequence](../../com.aspose.slides/isequence) - Het [ISequence](../../com.aspose.slides/isequence) object.