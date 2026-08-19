---
title: TrendlineCollection
second_title: Aspose.Slides för Java API-referens
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
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [add(int trendlineType)](#add-int-) | Lägger till den nya Trendline i slutet av en samling och returnerar den. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Tar bort det angivna värdet. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [getCount()](#getCount--) | Hämtar antalet element som faktiskt finns i samlingen. |
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
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - En java.util.Iterator för hela samlingen.
### getCount() {#getCount--}
```
public final int getCount()
```

Hämtar antalet element som faktiskt finns i samlingen. Skrivskyddad int.

**Returnerar:**
int