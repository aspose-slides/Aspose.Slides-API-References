---
title: LayoutSlideCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een basisklasse voor een collectie van layoutdia's.
type: docs
url: /nl/com.aspose.slides/layoutslidecollection/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

Stelt een basisklasse voor een collectie van layoutdia's.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [size()](#size--) | Retourneert het aantal layoutdia's in een collectie. |
| [get_Item(int index)](#get-Item-int-) | Retourneert de layoutdia op index. |
| [getByType(byte type)](#getByType-byte-) | Retourneert de eerste layoutdia van het opgegeven type. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Verwijdert een layout uit de collectie. |
| [removeUnused()](#removeUnused--) | Verwijdert ongebruikte layoutdia's (layoutdia's waarvan HasDependingSlides false is). |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen uit de collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatie-root. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```


Retourneert het aantal layoutdia's in een collectie. Alleen-lezen int.

**Retourneert:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```


Retourneert de layoutdia op index. Alleen-lezen [LayoutSlide](../../com.aspose.slides/layoutslide).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourneert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```


Retourneert de eerste layoutdia van het opgegeven type.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | byte | Een type layoutdia om te vinden. |

**Retourneert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) met het opgegeven type of null als er geen layouts zijn gevonden.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```


Verwijdert een layout uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | De layoutdia die uit de collectie moet worden verwijderd.

--------------------

1) Om het werpen van de PptxEditException te voorkomen, controleer eerst de HasDependingSlides-eigenschap van de layout. 2) Je kunt ook de [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove)-methode gebruiken om de code te vereenvoudigen. |
### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```


Verwijdert ongebruikte layoutdia's (layoutdia's waarvan HasDependingSlides false is).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```


Retourneert een enumerator die door de collectie itereert.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```


Retourneert een java-iterator voor de volledige collectie.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - Een java.util.Iterator voor de volledige collectie.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopieert alle elementen uit de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doelarray. |
| index | int | Startindex in de doelarray. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). Alleen-lezen boolean.

**Retourneert:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Retourneert een synchronisatie-root. Alleen-lezen Object.

**Retourneert:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retourneert Parent_Immediate-object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject