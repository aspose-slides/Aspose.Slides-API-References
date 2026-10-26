---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling punten voor die getekend moeten worden in de tweede taart of staaf in een staaf-van-taart of taart-van-staaf diagram met een aangepaste splitsing.
type: docs
url: /nl/com.aspose.slides/ipiesplitcustompointcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

Stelt een verzameling punten voor die getekend moeten worden in de tweede taart- of staaf in een staaf-van-taart- of taart-van-staaf-diagram met een aangepaste splitsing.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert het diagramdatapunt op index. |
| [add(int dataPointIndex)](#add-int-) | Voegt een datapunt toe op basis van de index in de puntenverzameling van de bovenliggende serie. |
| [remove(int dataPointIndex)](#remove-int-) | Verwijdert een item uit de verzameling op basis van de index in de puntenverzameling van de bovenliggende serie. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```


Retourneert het diagramdatapunt op index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het datapunt. |

**Retourneert:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Diagramdatapunt.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```


Voegt een datapunt toe op basis van de index in de puntenverzameling van de bovenliggende serie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataPointIndex | int | Index van het datapunt in de puntenverzameling van de bovenliggende serie. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```


Verwijdert een item uit de verzameling op basis van de index in de puntenverzameling van de bovenliggende serie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataPointIndex | int | Index van het datapunt in de puntenverzameling van de bovenliggende serie.. |