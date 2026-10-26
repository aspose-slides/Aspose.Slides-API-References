---
title: ISequenceCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av interaktiva sekvenser.
type: docs
url: /sv/com.aspose.slides/isequencecollection/
---
**Alla implementerade gränssnitt:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

Representerar en samling av interaktiva sekvenser.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCount()](#getCount--) | Returnerar antalet element i en samling skrivskyddad int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Lägg till en ny interaktiv sekvens. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Tar bort angiven sekvens från en samling. |
| [removeAt(int index)](#removeAt-int-) | Tar bort sekvens på det angivna indexet. |
| [clear()](#clear--) | Tar bort alla sekvenser från en samling. |
| [get_Item(int index)](#get-Item-int-) | Returnerar en sekvens på det angivna indexet. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Returnerar antalet element i en samling skrivskyddad int.

**Returnerar:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```

Lägg till en ny interaktiv sekvens.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | Shape-objekt [IShape](../../com.aspose.slides/ishape) |

**Returnerar:**
[ISequence](../../com.aspose.slides/isequence) - Ny sekvens [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```

Tar bort angiven sekvens från en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Sequence att ta bort. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort Sequence på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för element i samlingen int |
### clear() {#clear--}
```
public abstract void clear()
```

Tar bort alla sekvenser från en samling.
### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```

Returnerar en sekvens på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för element. |

**Returnerar:**
[ISequence](../../com.aspose.slides/isequence) - Objektet [ISequence](../../com.aspose.slides/isequence)