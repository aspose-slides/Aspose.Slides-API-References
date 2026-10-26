---
title: SmartArtShapeCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling van SmartArt-vormen voor
type: docs
url: /nl/com.aspose.slides/smartartshapecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
```
public class SmartArtShapeCollection implements ISmartArtShapeCollection
```

Represents a collection of a SmartArt shapes
## Methoden

| Methode | Omschrijving |
| --- | --- |
| [size()](#size--) | Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen van de collectie naar de opgegeven array. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de gehele collectie. |
### size() {#size--}
```
public final int size()
```


Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. Alleen-lezen int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtShape get_Item(int index)
```


Haalt het element op op de opgegeven index. Alleen-lezen [SmartArtShape](../../com.aspose.slides/smartartshape).

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| index | int | Index van vorm |

**Returns:**
[ISmartArtShape](../../com.aspose.slides/ismartartshape) - De SmartArt-vorm
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). Alleen-lezen boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Retourneert een synchronisatiewortel. Alleen-lezen Object.

**Returns:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopieert alle elementen van de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doel-array. |
| index | int | Startindex in de doel-array. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iterator()
```


Retourneert een enumerator die door de collectie iterereert.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iteratorJava()
```


Retourneert een java-iterator voor de gehele collectie.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - Een java.util.Iterator voor de gehele collectie.