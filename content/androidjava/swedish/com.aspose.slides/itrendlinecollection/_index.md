---
title: ITrendlineCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av TrendlineEx
type: docs
url: /sv/com.aspose.slides/itrendlinecollection/
---
**Alla implementerade gränssnitt:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

Representerar en samling av TrendlineEx
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [getCount()](#getCount--) | Hämtar antalet element som faktiskt finns i samlingen. |
| [add(int trendlineType)](#add-int-) | Lägger till den nya Trendline i slutet av en samling och returnerar den. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Tar bort det angivna värdet. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```

Hämtar elementet på det angivna indexet. Skrivskyddad [ITrendline](../../com.aspose.slides/itrendline).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Hämtar antalet element som faktiskt finns i samlingen. Skrivskyddad int.

**Returnerar:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```

Lägger till den nya Trendline i slutet av en samling och returnerar den.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| trendlineType | int | Trendline-typ [TrendlineType](../../com.aspose.slides/trendlinetype) |

**Returnerar:**
[ITrendline](../../com.aspose.slides/itrendline) - Ny Trendline [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```

Tar bort det angivna värdet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Trendline att ta bort [ITrendline](../../com.aspose.slides/itrendline) |