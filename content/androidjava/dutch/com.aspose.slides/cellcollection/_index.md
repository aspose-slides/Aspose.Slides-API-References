---
title: CellCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling cellen voor.
type: docs
url: /nl/com.aspose.slides/cellcollection/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), com.aspose.slides.IDOMObject
```
public abstract class CellCollection implements ICellCollection, IDOMObject
```

Stelt een verzameling cellen voor.
## Methoden

| Methode | Omschrijving |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | Retourneert het aantal cellen in een verzameling. |
| [get_Item(int index)](#get-Item-int-) | Retourneert een cel op basis van zijn positie. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de verzameling itereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige verzameling. |
| [getSlide()](#getSlide--) | Retourneert de bovenliggende dia van een CellCollection. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een CellCollection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen van de verzameling naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of toegang tot de verzameling gesynchroniseerd is (thread-veilig). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retourneert een Parent_Immediate-object. Alleen-lezen IDOMObject.

**Retour:**
com.aspose.slides.IDOMObject
### size() {#size--}
```
public final int size()
```


Retourneert het aantal cellen in een verzameling. Alleen-lezen int.

**Retour:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```


Retourneert een cel op basis van zijn positie. Alleen-lezen [Cell](../../com.aspose.slides/cell).

--------------------

Een Cell-object kan voor verschillende indexen worden geretourneerd wanneer een cel is samengevoegd.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[ICell](../../com.aspose.slides/icell)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iterator()
```


Retourneert een enumerator die door de verzameling itereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - Een IGenericEnumerator die kan worden gebruikt om door de verzameling te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```


Retourneert een java-iterator voor de volledige verzameling.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - Een java.util.Iterator voor de volledige verzameling.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Retourneert de bovenliggende dia van een CellCollection. Alleen-lezen [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Retour:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Retourneert de bovenliggende presentatie van een CellCollection. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retour:**
[IPresentation](../../com.aspose.slides/ipresentation)
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopieert alle elementen van de verzameling naar de opgegeven array.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doelarray. |
| index | int | Begindex in de doelarray. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Retourneert een waarde die aangeeft of toegang tot de verzameling gesynchroniseerd is (thread-veilig). Alleen-lezen boolean.

**Retour:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Retourneert een synchronisatiewortel. Alleen-lezen Object.

**Retour:**
java.lang.Object