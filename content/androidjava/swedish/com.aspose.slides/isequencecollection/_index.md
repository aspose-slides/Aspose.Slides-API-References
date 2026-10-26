---
title: ISequenceCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling interaktiva sekvenser.
type: docs
url: /sv/com.aspose.slides/isequencecollection/
---
**Alla implementerade gränssnitt:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

Representerar en samling interaktiva sekvenser.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCount()](#getCount--) | Returnerar antalet element i en samling Read-only int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Lägg till ny interaktiv sekvens. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Tar bort specificerad sekvens från en samling. |
| [removeAt(int index)](#removeAt-int-) | Tar bort sekvensen vid det specificerade indexet. |
| [clear()](#clear--) | Tar bort alla sekvenser från en samling. |
| [get_Item(int index)](#get-Item-int-) | Returnerar en sekvens vid det specificerade indexet. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Returnerar antalet element i en samling Read-only int.

**Returnerar:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```

Lägg till ny interaktiv sekvens.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | Formobjekt [IShape](../../com.aspose.slides/ishape) |

**Returnerar:**
[ISequence](../../com.aspose.slides/isequence) - Ny sekvens [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```

Tar bort specificerad sekvens från en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Sekvens att ta bort. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort sekvensen vid det specificerade indexet.

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

Returnerar en sekvens vid det specificerade indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för elementet. |

**Returnerar:**
[ISequence](../../com.aspose.slides/isequence) - Det [ISequence](../../com.aspose.slides/isequence)-objektet.