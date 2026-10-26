---
title: SmartArtNodeCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av SmartArt-noder.
type: docs
url: /sv/com.aspose.slides/smartartnodecollection/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

Representerar en samling av SmartArt-noder.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar noden vid index |
| [size()](#size--) | Returnerar antalet noder i samlingen Skrivskyddad int Skrivskyddad int. |
| [addNode()](#addNode--) | Lägg till ny smart art nod eller undernod. |
| [removeNode(int index)](#removeNode-int-) | Ta bort nod eller undernod efter index |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Ta bort nod eller undernod |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Lägg till ny nod i den valda positionen i nodsamlingen |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar alla element från samlingen till den angivna arrayen. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar huruvida åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar en synkroniseringsrot. |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

Returnerar noden vid index

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet |

**Returnerar:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - SmartArt-noden
### size() {#size--}
```
public final int size()
```

Returnerar antalet noder i samlingen Skrivskyddad int Skrivskyddad int.

**Returnerar:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

Lägg till ny smart art nod eller undernod.

**Returnerar:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Tillagd nod
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

Ta bort nod eller undernod efter index

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Nollbaserat index för noden |
### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

Ta bort nod eller undernod

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Nod att ta bort |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

Lägg till ny nod i den valda positionen i nodsamlingen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | int | Nollbaserad nodposition |

**Returnerar:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Tillagd nod
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - En java.util.Iterator för hela samlingen.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopierar alla element från samlingen till den angivna arrayen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Målarray. |
| index | int | Startindex i målarrayen. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Returnerar ett värde som indikerar huruvida åtkomst till samlingen är synkroniserad (trådsäker). Skrivskyddad boolean .

**Returnerar:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Returnerar en synkroniseringsrot. Skrivskyddad Object.

**Returnerar:**
java.lang.Object