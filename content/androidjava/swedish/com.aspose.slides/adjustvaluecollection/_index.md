---
title: AdjustValueCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av shape's justeringar.
type: docs
url: /sv/com.aspose.slides/adjustvaluecollection/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
```
public final class AdjustValueCollection extends DomObject<GeometryShape> implements IAdjustValueCollection
```

Representerar en samling av shape's justeringar.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [size()](#size--) | Returnerar ett antal justeringar. |
| [get_Item(int index)](#get-Item-int-) | Returnerar justering efter index. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar alla element från samlingen till den angivna arrayen. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar ett synkroniseringsrot. |
| [iterator()](#iterator--) | Returnerar en enumerator för hela samlingen. |
### size() {#size--}
```
public final int size()
```


Returnerar ett antal justeringar. Skrivskyddad int.

**Returnerar:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAdjustValue get_Item(int index)
```


Returnerar justering efter index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | justeringens index. |

**Returnerar:**
[IAdjustValue](../../com.aspose.slides/iadjustvalue) - [AdjustValue](../../com.aspose.slides/adjustvalue).
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


Returnerar en synkroniseringsrot. Skrivskyddad Object.

**Returnerar:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.IEnumerator iterator()
```


Returnerar en enumerator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.IEnumerator