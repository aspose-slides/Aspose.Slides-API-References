---
title: SequenceCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie van interactieve sequenties voor.
type: docs
url: /nl/com.aspose.slides/sequencecollection/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

Stelt een collectie van interactieve sequenties voor.
## Methoden

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Retourneert het aantal elementen in een collectie Alleen-lezen int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Voeg een nieuwe interactieve sequentie toe. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Verwijdert de opgegeven sequentie uit een collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert de sequentie op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle sequenties uit een collectie. |
| [get_Item(int index)](#get-Item-int-) | Retourneert een sequentie op de opgegeven index. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereren. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
### getCount() {#getCount--}
```
public final int getCount()
```


Retourneert het aantal elementen in een collectie Alleen-lezen int.

**Retour:**  
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```


Voeg een nieuwe interactieve sequentie toe. Lezen/Schrijven [Sequence](../../com.aspose.slides/sequence).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**Retour:**  
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```


Verwijdert de opgegeven sequentie uit een collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Sequentie om te verwijderen. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Verwijdert de sequentie op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een sequentie die verwijderd moet worden. |
### clear() {#clear--}
```
public final void clear()
```


Verwijdert alle sequenties uit een collectie.
### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```


Retourneert een sequentie op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van element. |

**Retour:**  
[ISequence](../../com.aspose.slides/isequence) - Het [ISequence](../../com.aspose.slides/isequence) object.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```


Retourneert een enumerator die door de collectie itereren.

**Retour:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```


Retourneert een java-iterator voor de volledige collectie.

**Retour:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Een java.util.Iterator voor de volledige collectie.