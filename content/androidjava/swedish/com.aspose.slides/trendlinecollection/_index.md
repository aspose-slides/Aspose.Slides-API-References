---
title: TrendlineCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av Trendline
type: docs
url: /sv/com.aspose.slides/trendlinecollection/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

Representerar en samling av Trendline
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [add(int trendlineType)](#add-int-) | Adds the new Trendline at the end of a collection and return it. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Removes the specified value. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [getCount()](#getCount--) | Gets the number of elements actually contained in the collection. |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```

Hämtar elementet på det angivna indexet. Skrivskyddad [Trendline](../../com.aspose.slides/trendline).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[ITrendline](../../com.aspose.slides/itrendline)
### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```

Lägger till den nya Trendline i slutet av en samling och returnerar den.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| trendlineType | int |  |

**Returnerar:**
[ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```

Tar bort det angivna värdet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - An java.util.Iterator for the entire collection.
### getCount() {#getCount--}
```
public final int getCount()
```

Hämtar antalet element som faktiskt finns i samlingen. Skrivskyddad int.

**Returnerar:**
int