---
title: SmartArtNodeCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling SmartArt-knopen voor.
type: docs
url: /nl/com.aspose.slides/smartartnodecollection/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

Stelt een verzameling SmartArt-knopen voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert knoop op index |
| [size()](#size--) | Retourneert het aantal knopen in de collectie Alleen-lezen  int  Alleen-lezen  int . |
| [addNode()](#addNode--) | Voegt een nieuwe smart art-knoop of subknoop toe. |
| [removeNode(int index)](#removeNode-int-) | Verwijdert knoop of subknoop op index |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Verwijdert knoop of subknoop |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Voegt een nieuwe knoop toe op de geselecteerde positie in de knoopverzameling |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen van de collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```


Retourneert knoop op index

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het element |

**Returns:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - De SmartArt-knoop
### size() {#size--}
```
public final int size()
```


Retourneert het aantal knopen in de collectie Alleen-lezen  int  Alleen-lezen  int .

**Returns:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```


Voegt een nieuwe smart art-knoop of subknoop toe.

**Returns:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Toegevoegde knoop
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```


Verwijdert knoop of subknoop op index

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Nulgebaseerde index van de knoop |

### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```


Verwijdert knoop of subknoop

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Knoop om te verwijderen |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```


Voegt een nieuwe knoop toe op de geselecteerde positie in de knoopverzameling

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | int | Nulgebaseerde knooppositie |

**Returns:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Toegevoegde knoop
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```


Retourneert een enumerator die door de collectie itereert.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```


Retourneert een java-iterator voor de volledige collectie.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Een java.util.Iterator voor de volledige collectie.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopieert alle elementen van de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doel-array. |
| index | int | Startindex in de doel-array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). Alleen-lezen  boolean .

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Retourneert een synchronisatiewortel. Alleen-lezen Object.

**Returns:**
java.lang.Object