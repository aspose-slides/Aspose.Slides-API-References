---
title: SequenceCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av interaktiva sekvenser.
type: docs
url: /sv/com.aspose.slides/sequencecollection/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

Representerar en samling av interaktiva sekvenser.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCount()](#getCount--) | Returnerar antalet element i en samling Skrivskyddad int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Lägg till en ny interaktiv sekvens. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Tar bort specificerad sekvens från en samling. |
| [removeAt(int index)](#removeAt-int-) | Tar bort sekvens på det angivna indexet. |
| [clear()](#clear--) | Tar bort alla sekvenser från en samling. |
| [get_Item(int index)](#get-Item-int-) | Returnerar en sekvens på det angivna indexet. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
### getCount() {#getCount--}
```
public final int getCount()
```

Returnerar antalet element i en samling Skrivskyddad int.

**Returnerar:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```

Lägg till en ny interaktiv sekvens. Läs/skriv [Sequence](../../com.aspose.slides/sequence).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**Returnerar:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```

Tar bort specificerad sekvens från en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Sekvens att ta bort. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Tar bort sekvens på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för sekvens som ska tas bort. |

### clear() {#clear--}
```
public final void clear()
```

Tar bort alla sekvenser från en samling.

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```

Returnerar en sekvens på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för element. |

**Returnerar:**
[ISequence](../../com.aspose.slides/isequence) - [ISequence](../../com.aspose.slides/isequence)-objektet.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - En java.util.Iterator för hela samlingen.