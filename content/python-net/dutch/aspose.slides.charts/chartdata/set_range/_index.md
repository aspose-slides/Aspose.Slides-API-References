---
title: set_range method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
Stel het gegevensbereik van de grafiek in. Series en categorieën worden bijgewerkt op basis van het nieuwe gegevensbereik.
            Als het aantal series in het gegevensbereik groter is dan het aantal series in de grafiekgegevens, dan wordt er een extra serie met hetzelfde type als de laatste serie in de huidige collectie aan het einde van de collectie toegevoegd.


```python
def set_range(self, formula):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| formula | **str** | De cellen-gegevensbereik-formule. Bijv: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula is None. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Niet-ondersteund grafiektype |
| **RuntimeError(Proxy error(ArgumentException))** | formula heeft een onjuiste indeling. |



### Zie ook
* klasse [`ChartData`](/slides/python-net/nl/aspose.slides.charts/chartdata)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)