---
title: set_external_workbook method
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
Stelt een externe werkmap in als gegevensbron voor de grafiek. Grafiekgegevens worden bijgewerkt vanuit de doelwerkmap.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| workbook_path | **str** | Pad naar de doelwerkmap |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Externe werkmap is niet beschikbaar of kan niet worden geladen. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Stelt een externe werkmap in als gegevensbron voor de grafiek.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| workbook_path | **str** | Pad naar de doelwerkmap |
| update_chart_data | **bool** | Als de waarde false is, wordt alleen het pad naar de werkmap bijgewerkt. <br/><br/>             Grafiekgegevens worden niet geladen en bijgewerkt vanuit de doelwerkmap. Kan worden gebruikt wanneer de doelwerkmap niet bestaat of niet beschikbaar is.<br/><br/>             Als de waarde true is, worden grafiekgegevens bijgewerkt vanuit de doelwerkmap. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Externe werkmap is niet beschikbaar of kan niet worden geladen. |



### Zie ook
* klasse [`IChartData`](/slides/python-net/nl/aspose.slides.charts/ichartdata)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)