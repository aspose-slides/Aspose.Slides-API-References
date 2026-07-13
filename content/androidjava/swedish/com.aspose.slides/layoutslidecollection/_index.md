---
title: LayoutSlideCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en basklass för en samling av layoutbilder.
type: docs
url: /sv/com.aspose.slides/layoutslidecollection/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

Representerar en basklass för en samling av layout-bilder.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [size()](#size--) | Returnerar antalet layout-bilder i en samling. |
| [get_Item(int index)](#get-Item-int-) | Returnerar layout-bilden med index. |
| [getByType(byte type)](#getByType-byte-) | Returnerar den första layout-bilden av angiven typ. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Tar bort en layout från samlingen. |
| [removeUnused()](#removeUnused--) | Tar bort oanvända layout-bilder (layout-bilder vars HasDependingSlides är false). |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar alla element från samlingen till den angivna arrayen. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar ett synkroniseringsrot. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

Returnerar antalet layout-bilder i en samling. Skrivskyddad int.

**Returnerar:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```

Returnerar layout-bilden med index. Skrivskyddad [LayoutSlide](../../com.aspose.slides/layoutslide).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```

Returnerar den första layout-bilden av angiven typ.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | byte | En typ av layout-bild att hitta. |

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) med angiven typ eller null om inga layouter hittades.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```

Tar bort en layout från samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout-bilden som ska tas bort från samlingen.

--------------------

1) För att undvika att PptxEditException kastas, kontrollera layoutens HasDependingSlides-egenskap först. 2) Du kan också använda [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove)-metoden för att förenkla koden. |
### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```

Tar bort oanvända layout-bilder (layout-bilder vars HasDependingSlides är false).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - En java.util.Iterator för hela samlingen.
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

Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). Skrivskyddad boolean.

**Returnerar:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Returnerar ett synkroniseringsrot. Skrivskyddad Object.

**Returnerar:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objektet. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject