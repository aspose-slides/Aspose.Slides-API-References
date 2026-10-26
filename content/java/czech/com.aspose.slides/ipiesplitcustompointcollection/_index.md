---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides pro Java - reference API
description: Representuje kolekci bodů, které mají být vykresleny ve druhém výseku koláče nebo sloupce v grafu typu bar-of-pie nebo pie-of-pie s vlastním rozdělením.
type: docs
url: /cs/com.aspose.slides/ipiesplitcustompointcollection/
---
**Všechny implementované rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

Representuje kolekci bodů, které mají být vykresleny ve druhém výseku koláče nebo sloupce v grafu typu bar-of-pie nebo pie-of-pie s vlastním rozdělením.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací datový bod grafu podle indexu. |
| [add(int dataPointIndex)](#add-int-) | Přidá datový bod podle jeho indexu v kolekci bodů nadřazené řady. |
| [remove(int dataPointIndex)](#remove-int-) | Odstraní položku z kolekce podle jejího indexu v kolekci bodů nadřazené řady. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```


Vrací datový bod grafu podle indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index datového bodu. |

**Vrací:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Datový bod grafu.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```


Přidá datový bod podle jeho indexu v kolekci bodů nadřazené řady.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| dataPointIndex | int | Index datového bodu v kolekci bodů nadřazené řady. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```


Odstraní položku z kolekce podle jejího indexu v kolekci bodů nadřazené řady.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| dataPointIndex | int | Index datového bodu v kolekci bodů nadřazené řady.. |