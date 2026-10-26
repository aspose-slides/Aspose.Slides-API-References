---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides voor Java API-referentie
description: Representeert een verzameling punten die getekend moeten worden in de tweede taart of staaf van een staaf-in-taart of taart-in-staaf diagram met een aangepaste splitsing.
type: docs
url: /nl/com.aspose.slides/ipiesplitcustompointcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

Stelt een verzameling punten voor die getekend moeten worden in de tweede taart of staaf van een staaf-in-taart of taart-in-staaf diagram met een aangepaste splitsing.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert diagramdatapunt op basis van de index. |
| [add(int dataPointIndex)](#add-int-) | Voegt datapunt toe op basis van de index in de puntenverzameling van de bovenliggende serie. |
| [remove(int dataPointIndex)](#remove-int-) | Verwijdert item uit de verzameling op basis van de index in de puntenverzameling van de bovenliggende serie. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Retourneert diagramdatapunt op basis van de index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van datapunt. |

**Retourwaarde:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Diagramdatapunt.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```

Voegt datapunt toe op basis van de index in de puntenverzameling van de bovenliggende serie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataPointIndex | int | Index van datapunt in de puntenverzameling van de bovenliggende serie. |
### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

Verwijdert item uit de verzameling op basis van de index in de puntenverzameling van de bovenliggende serie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dataPointIndex | int | Index van datapunt in de puntenverzameling van de bovenliggende serie.. |