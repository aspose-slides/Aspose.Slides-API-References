---
title: LayoutSlideCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een basisklasse voor een collectie van lay-outdia's.
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

Stelt een basisklasse voor een collectie van lay-out-dia's.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [size()](#size--) | Retourneert het aantal lay-out-dia's in een collectie. |
| [get_Item(int index)](#get-Item-int-) | Retourneert de lay-out-dia op index. |
| [getByType(byte type)](#getByType-byte-) | Retourneert de eerste lay-out-dia van het opgegeven type. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Verwijdert een lay-out uit de collectie. |
| [removeUnused()](#removeUnused--) | Verwijdert ongebruikte lay-out-dia's (lay-out-dia's waarvan HasDependingSlides onwaar is). |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen van de collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of toegang tot de collectie gesynchroniseerd is (thread-veilig). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

Retourneert het aantal lay-out-dia's in een collectie. Alleen-lezen int.

**Retour:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```

Retourneert de lay-out-dia op index. Alleen-lezen [LayoutSlide](../../com.aspose.slides/layoutslide).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```

Retourneert de eerste lay-out-dia van het opgegeven type.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | byte | Een type lay-out-dia om te vinden. |

**Retour:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) met opgegeven type of null als er geen lay-outs zijn gevonden.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```

Verwijdert een lay-out uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | De lay-out-dia die uit de collectie moet worden verwijderd. |

--------------------

1) Om het werpen van de PptxEditException te voorkomen, controleer de HasDependingSlides-eigenschap van de lay-out van tevoren. 2) U kunt ook de [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove)-methode gebruiken om de code te vereenvoudigen. |
### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```

Verwijdert ongebruikte lay-out-dia's (lay-out-dia's waarvan HasDependingSlides onwaar is).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```

Retourneert een enumerator die door de collectie itereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```

Retourneert een java-iterator voor de volledige collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - Een java.util.Iterator voor de volledige collectie.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopieert alle elementen van de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doelarray. |
| index | int | Startindex in de doelarray. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retourneert een waarde die aangeeft of toegang tot de collectie gesynchroniseerd is (thread-veilig). Alleen-lezen boolean.

**Retour:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retourneert een synchronisatiewortel. Alleen-lezen Object.

**Retour:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert een Parent_Immediate-object. Alleen-lezen IDOMObject.

**Retour:**
com.aspose.slides.IDOMObject