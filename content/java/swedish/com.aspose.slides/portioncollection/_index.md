---
title: PortionCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av portioner.
type: docs
url: /sv/com.aspose.slides/portioncollection/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

Representerar en samling av Portion.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCount()](#getCount--) | Hämtar antalet element som faktiskt finns i samlingen. |
| [isReadOnly()](#isReadOnly--) | Hämtar ett värde som indikerar om [IGenericCollection](../../com.aspose.slides/igenericcollection) är skrivskyddad. |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | Hämtar elementet på det angivna indexet. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Lägger till en Portion i slutet av samlingen. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Bestämmer indexet för ett specifikt objekt i Listan. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Infogar en Portion i samlingen på det angivna indexet. |
| [clear()](#clear--) | Tar bort alla element från samlingen. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Bestämmer om [IGenericCollection](../../com.aspose.slides/igenericcollection) innehåller ett specifikt värde. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | Kopierar elementen i [IGenericCollection](../../com.aspose.slides/igenericcollection) till en Array, med start vid ett specifikt Array-index. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Tar bort den första förekomsten av ett specifikt objekt från [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Tar bort elementet på det angivna indexet i samlingen. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
### getCount() {#getCount--}
```
public final int getCount()
```

Hämtar antalet element som faktiskt finns i samlingen. Skrivskyddad int.

**Returnerar:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Hämtar ett värde som indikerar om [IGenericCollection](../../com.aspose.slides/igenericcollection) är skrivskyddad. Skrivskyddad boolean.

**Returnerar:**
boolean - true om [IGenericCollection](../../com.aspose.slides/igenericcollection) är skrivskyddad; annars false.
### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```

Hämtar elementet på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IPortion](../../com.aspose.slides/iportion)
### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```

Hämtar elementet på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```

Lägger till en Portion i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Portionen som ska läggas till i slutet av samlingen. |
### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```

Bestämmer indexet för ett specifikt objekt i Listan.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Objektet att hitta i Listan. |

**Returnerar:**
int - Indexet för item om det finns i listan; annars -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```

Infogar en Portion i samlingen på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet där Portion ska infogas. |
| value | [IPortion](../../com.aspose.slides/iportion) | Portionen som ska infogas. |
### clear() {#clear--}
```
public final void clear()
```

Tar bort alla element från samlingen.
### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```

Bestämmer om [IGenericCollection](../../com.aspose.slides/igenericcollection) innehåller ett specifikt värde.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Objektet att hitta i [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returnerar:**
boolean - true om item finns i [IGenericCollection](../../com.aspose.slides/igenericcollection); annars false.
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

Kopierar elementen i [IGenericCollection](../../com.aspose.slides/igenericcollection) till en Array, med start vid ett specifikt Array-index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | Den endimensionella Array som är mål för elementen kopierade från [IGenericCollection](../../com.aspose.slides/igenericcollection). Arrayen måste ha nollbaserad indexering. |
| arrayIndex | int | Det nollbaserade indexet i array där kopieringen börjar. |
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

Tar bort den första förekomsten av ett specifikt objekt från [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Objektet att ta bort från [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returnerar:**
boolean - true om item lyckades tas bort från [IGenericCollection](../../com.aspose.slides/igenericcollection); annars false. Denna metod returnerar också false om item inte hittas i den ursprungliga [IGenericCollection](../../com.aspose.slides/igenericcollection).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Tar bort elementet på det angivna indexet i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet som ska tas bort. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - En java.util.Iterator för hela samlingen.