---
title: BehaviorCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av beteendeeffekter.
type: docs
url: /sv/com.aspose.slides/behaviorcollection/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

Representerar en samling av beteendeeffekter.
## Metoder

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Returnerar antalet beteenden i en samling. |
| [isReadOnly()](#isReadOnly--) | Hämtar ett värde som indikerar om [IGenericCollection](../../com.aspose.slides/igenericcollection) är skrivskyddad. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Lägg till ett nytt beteende i en samling. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Bestämmer index för ett specifikt objekt i Listan. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Infogar ett nytt beteende i en samling på angivet index. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | Kopierar elementen i [IGenericCollection](../../com.aspose.slides/igenericcollection) till en Array, med start vid ett specifikt Array-index. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Tar bort angivet beteende från en samling. |
| [removeAt(int index)](#removeAt-int-) | Tar bort ett beteende från en samling på det angivna indexet. |
| [clear()](#clear--) | Tar bort alla beteenden från en samling. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Bestämmer om [IGenericCollection](../../com.aspose.slides/igenericcollection) innehåller ett specifikt värde. |
| [get_Item(int index)](#get-Item-int-) | Returnerar ett beteende på det angivna indexet. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Sätter ett beteende på det angivna indexet. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
### getCount() {#getCount--}
```
public final int getCount()
```


Returnerar antalet beteenden i en samling. Skrivskyddad int.

**Returnerar:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Hämtar ett värde som indikerar om [IGenericCollection](../../com.aspose.slides/igenericcollection) är skrivskyddad. Skrivskyddad boolean.

**Returnerar:**
boolean - true om [IGenericCollection](../../com.aspose.slides/igenericcollection) är skrivskyddad; annars false.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```


Lägg till ett nytt beteende i en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Beteende att lägga till. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```


Bestämmer index för ett specifikt objekt i Listan.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Objektet att hitta i Listan. |

**Returnerar:**
int - Index för objektet om det hittas i listan; annars -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```


Infogar ett nytt beteende i en samling på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index där det nya beteendet ska infogas. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Beteende att infoga. |

### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```


Kopierar elementen i [IGenericCollection](../../com.aspose.slides/igenericcollection) till en Array, med start vid ett specifikt Array-index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | Den endimensionella Array som är destinationen för elementen som kopierats från [IGenericCollection](../../com.aspose.slides/igenericcollection). Arrayen måste ha nollbaserad indexering. |
| arrayIndex | int | Det nollbaserade indexet i arrayen där kopieringen börjar. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```


Tar bort angivet beteende från en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Beteende att ta bort. |

**Returnerar:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Tar bort ett beteende från en samling på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för ett beteende att ta bort. |

### clear() {#clear--}
```
public final void clear()
```


Tar bort alla beteenden från en samling.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```


Bestämmer om [IGenericCollection](../../com.aspose.slides/igenericcollection) innehåller ett specifikt värde.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Objektet att hitta i [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returnerar:**
boolean - true om objektet hittas i [IGenericCollection](../../com.aspose.slides/igenericcollection); annars false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
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
public final void set_Item(int index, IBehavior value)
```


Sätter ett beteende på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för ett beteende att returnera. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```


Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```


Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - En java.util.Iterator för hela samlingen.