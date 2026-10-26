---
title: SmartArtNodeCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een collectie van SmartArt-knooppunten voor.
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

Stelt een collectie van SmartArt-knooppunten voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns node by index |
| [size()](#size--) | Returns count of nodes in collection Read-only  int  Read-only  int . |
| [addNode()](#addNode--) | Add new smart art node or sub node. |
| [removeNode(int index)](#removeNode-int-) | Remove node or sub node by index |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Remove node or sub node |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Add new node in the selected position of nodes collection |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

Retourneert knooppunt op index

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index van het element |

**Retour:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - De SmartArt-knooppunt
### size() {#size--}
```
public final int size()
```

Retourneert het aantal knooppunten in de collectie Alleen-lezen int Alleen-lezen int .

**Retour:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

Voegt een nieuw smart-art-knooppunt of subknooppunt toe.

**Retour:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Toegevoegde knooppunt
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

Verwijdert knooppunt of subknooppunt op index

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Nul-gebaseerde index van knooppunt |
### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

Verwijdert knooppunt of subknooppunt

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Knooppunt om te verwijderen |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

Voegt een nieuw knooppunt toe op de geselecteerde positie in de knooppuntencollectie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| position | int | Nul-gebaseerde knooppuntpositie |

**Retour:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Toegevoegde knooppunt
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

Retourneert een enumerator die door de collectie iterereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

Retourneert een java-iterator voor de volledige collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopieert alle elementen van de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doel-array. |
| index | int | Beginnende index in de doel-array. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd (thread-safe) is. Alleen-lezen boolean .

**Retour:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retourneert een synchronisatiewortel. Alleen-lezen Object.

**Retour:**
java.lang.Object