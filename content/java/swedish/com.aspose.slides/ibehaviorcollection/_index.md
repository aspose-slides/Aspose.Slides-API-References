---
title: IBehaviorCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av beteendereffekter.
type: docs
url: /sv/com.aspose.slides/ibehaviorcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

Representerar en samling av beteendereffekter.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar ett beteende på det angivna indexet. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Returnerar ett beteende på det angivna indexet. |
| [getCount()](#getCount--) | Returnerar antalet beteenden i en samling. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Lägg till nytt beteende i en samling. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Bestämmer indexet för ett specifikt objekt i List. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Infogar nytt beteende i en samling på det angivna indexet. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Tar bort specificerat beteende från en samling. |
| [removeAt(int index)](#removeAt-int-) | Tar bort ett beteende från en samling på det angivna indexet. |
| [clear()](#clear--) | Tar bort alla beteenden från en samling. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Bestämmer om [IGenericCollection](../../com.aspose.slides/igenericcollection) innehåller ett specifikt värde. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```

Returnerar ett beteende på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för ett beteende att returnera. |

**Returnerar:**
[IBehavior](../../com.aspose.slides/ibehavior) - Animationsbeteende.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```

Returnerar ett beteende på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för ett beteende att returnera. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Returnerar antalet beteenden i en samling. Skrivskyddad int.

**Returnerar:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

Lägg till nytt beteende i en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Beteende att lägga till. |
### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```

Bestämmer indexet för ett specifikt objekt i List.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Objektet att hitta i List. |

**Returnerar:**
int - Indexet för objektet om det finns i listan; annars -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

Infogar nytt beteende i en samling på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index där det nya beteendet ska infogas. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Beteende att infoga. |
### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

Tar bort specificerat beteende från en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Beteende att ta bort. |

**Returnerar:**
boolean - Sant om ett beteende har tagits bort framgångsrikt boolean
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort ett beteende från en samling på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för ett beteende att ta bort. |
### clear() {#clear--}
```
public abstract void clear()
```

Tar bort alla beteenden från en samling.
### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```

Bestämmer om [IGenericCollection](../../com.aspose.slides/igenericcollection) innehåller ett specifikt värde.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Objektet att hitta i [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returnerar:**
boolean - sant om objektet hittas i [IGenericCollection](../../com.aspose.slides/igenericcollection); annars falskt.