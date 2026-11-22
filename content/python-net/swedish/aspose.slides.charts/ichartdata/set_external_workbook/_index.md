---
title: set_external_workbook method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
Ställer in extern arbetsbok som datakälla för diagrammet. Diagramdata kommer att uppdateras från målarbetsboken.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| workbook_path | **str** | Sökväg till målarbetsboken |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Den externa arbetsboken är inte tillgänglig eller kan inte laddas. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Ställer in extern arbetsbok som datakälla för diagrammet.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| workbook_path | **str** | Sökväg till målarbetsboken |
| update_chart_data | **bool** | Om värdet är falskt uppdateras endast arbetsbokens sökväg. <br/><br/>Diagramdata kommer inte att laddas och uppdateras från målarbetsboken. Kan användas när målarbetsboken inte finns eller inte är tillgänglig.<br/><br/>Om värdet är sant uppdateras diagramdata från målarbetsboken. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Den externa arbetsboken är inte tillgänglig eller kan inte laddas. |



### Se också
* klass [`IChartData`](/slides/python-net/sv/aspose.slides.charts/ichartdata)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)