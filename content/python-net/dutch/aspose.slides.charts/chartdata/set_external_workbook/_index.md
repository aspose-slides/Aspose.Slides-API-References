---
title: set_external_workbook method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
Stelt een extern werkboek in als gegevensbron voor de grafiek. Grafiekgegevens worden bijgewerkt vanuit het doelwerkboek.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| workbook_path | **str** | Pad naar het doelwerkboek |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Extern werkboek is niet beschikbaar of kan niet worden geladen. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Stelt een extern werkboek in als gegevensbron voor de grafiek.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| workbook_path | **str** | Pad naar het doelwerkboek |
| update_chart_data | **bool** | Als de waarde false is wordt alleen het werkboekpad bijgewerkt. <br/><br/>             Grafiekgegevens worden niet geladen en bijgewerkt vanuit het doelwerkboek. Kan worden gebruikt wanneer het doelwerkboek niet bestaat of niet beschikbaar is.<br/><br/>             Als de waarde true is worden grafiekgegevens bijgewerkt vanuit het doelwerkboek. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Extern werkboek is niet beschikbaar of kan niet worden geladen. |



### Zie ook
* klasse [`ChartData`](/slides/python-net/nl/aspose.slides.charts/chartdata)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)