---
title: GradientStopCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling gradientstopp.
type: docs
url: /sv/com.aspose.slides/gradientstopcollection/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

Representerar en samling gradientstopp.
## Methods

| Metod | Beskrivning |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | Returnerar antalet gradientstopp i en samling. |
| [get_Item(int index)](#get-Item-int-) | Returnerar gradientstoppet vid index. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Skapar ett nytt gradientstopp och lägger till det i slutet av samlingen. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Skapar ett nytt gradientstopp och lägger till det i slutet av samlingen. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Skapar ett nytt gradientstopp och lägger till det i slutet av samlingen. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Skapar ett nytt gradientstopp och infogar det på angivet index i samlingen. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Skapar ett nytt gradientstopp och infogar det på angivet index i samlingen. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Skapar ett nytt gradientstopp och infogar det på angivet index i samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort ett gradientstopp på det angivna indexet. |
| [clear()](#clear--) | Tar bort alla gradientstopp från en samling. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar alla element från samlingen till den angivna arrayen. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar en synkroniseringsrot. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Endast läs long.

**Returnerar:**
long
### size() {#size--}
```
public final int size()
```

Returnerar antalet gradientstopp i en samling. Endast läs int .

**Returnerar:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```

Returnerar gradientstoppet vid index.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public final IGradientStop add(float position, Integer color)
```

Skapar ett nytt gradientstopp och lägger till det i slutet av samlingen.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | float | Position för det nya gradientstoppet. |
| color | java.lang.Integer | Färg på det nya gradientstoppet. |

**Returnerar:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index för det nya gradientstoppet i samlingen.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```

Skapar ett nytt gradientstopp och lägger till det i slutet av samlingen.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | float | Position för det nya gradientstoppet. |
| presetColor | int | Färg på det nya gradientstoppet. |

**Returnerar:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index för det nya gradientstoppet i samlingen.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```

Skapar ett nytt gradientstopp och lägger till det i slutet av samlingen.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | float | Position för det nya gradientstoppet. |
| schemeColor | int | Färg på det nya gradientstoppet. |

**Returnerar:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index för det nya gradientstoppet i samlingen.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public final void insert(int index, float position, Integer color)
```

Skapar ett nytt gradientstopp och infogar det på angivet index i samlingen.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index i samlingen där det nya gradientstoppet ska infogas. |
| position | float | Position för det nya gradientstoppet. |
| color | java.lang.Integer | Färg på det nya gradientstoppet. |
### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```

Skapar ett nytt gradientstopp och infogar det på angivet index i samlingen.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index i samlingen där det nya gradientstoppet ska infogas. |
| position | float | Position för det nya gradientstoppet. |
| presetColor | int | Färg på det nya gradientstoppet. |
### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```

Skapar ett nytt gradientstopp och infogar det på angivet index i samlingen.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index i samlingen där det nya gradientstoppet ska infogas. |
| position | float | Position för det nya gradientstoppet. |
| schemeColor | int | Färg på det nya gradientstoppet. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Tar bort ett gradientstopp på det angivna indexet.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för ett gradientstopp som ska raderas. |
### clear() {#clear--}
```
public final void clear()
```

Tar bort alla gradientstopp från en samling.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - En java.util.Iterator för hela samlingen.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopierar alla element från samlingen till den angivna arrayen.

**Parameter:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Målarray. |
| index | int | Startindex i målarryen. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). Endast läs boolean .

**Returnerar:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Returnerar en synkroniseringsrot. Endast läs Object.

**Returnerar:**
java.lang.Object