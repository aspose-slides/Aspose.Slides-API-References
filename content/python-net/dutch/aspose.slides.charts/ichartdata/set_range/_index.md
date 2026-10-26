---
title: set_range method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/ichartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
Stel het gegevensbereik van de grafiek in. Reeksen en categorieën worden bijgewerkt op basis van het nieuwe gegevensbereik.
Als het aantal reeksen in het gegevensbereik groter is dan het aantal reeksen in de grafiekgegevens, wordt een extra reeks met hetzelfde type als de laatste reeks in de huidige collectie aan het einde van de collectie toegevoegd.


```python
def set_range(self, formula):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| formula | **str** | De formule voor het cellen-bereik. Bijv.: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula is None. |
| **RuntimeError(Proxy error(ArgumentException))** | formula heeft een onjuiste indeling. |



### Zie ook
* klasse [`IChartData`](/slides/python-net/nl/aspose.slides.charts/ichartdata)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)