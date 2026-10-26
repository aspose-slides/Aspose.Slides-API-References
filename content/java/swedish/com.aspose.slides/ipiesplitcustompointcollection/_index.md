---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av punkter som ska ritas i den andra pajen eller stapeln i ett stapel-i-paj- eller paj-i-stapel-diagram med en anpassad uppdelning.
type: docs
url: /sv/com.aspose.slides/ipiesplitcustompointcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

Representerar en samling av punkter som ska ritas i den andra pajen eller stapeln på ett stapel-i-paj- eller paj-i-stapel-diagram med en anpassad uppdelning.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar diagramdatapunkt efter index. |
| [add(int dataPointIndex)](#add-int-) | Lägger till datapunkt efter dess index i föräldrakollektionens seriepunktslista. |
| [remove(int dataPointIndex)](#remove-int-) | Tar bort objekt från kollektionen efter dess index i föräldrakollektionens seriepunktslista. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Returnerar diagramdatapunkt efter index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för datapunkt. |

**Returnerar:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) – Diagramdatapunkt.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```

Lägger till datapunkt efter dess index i föräldrakollektionens seriepunktslista.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataPointIndex | int | Index för datapunkt i föräldrakollektionens seriepunktslista. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

Tar bort objekt från kollektionen efter dess index i föräldrakollektionens seriepunktslista.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dataPointIndex | int | Index för datapunkt i föräldrakollektionens seriepunktslista.. |