---
title: set_external_workbook method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
Ställer in extern arbetsbok som en datakälla för diagrammet. Diagramdata kommer att uppdateras från målarboken.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| workbook_path | **str** | Sökväg till målarboken |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Extern arbetsbok är inte tillgänglig eller kan inte laddas. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Ställer in extern arbetsbok som en datakälla för diagrammet.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| workbook_path | **str** | Sökväg till målarboken |
| update_chart_data | **bool** | Om värdet är falskt uppdateras endast arbetsbokens sökväg. <br/><br/>             Diagramdata kommer inte att laddas och uppdateras från målarboken. Kan användas när målarboken inte finns eller inte är tillgänglig.<br/><br/>             Om värdet är sant uppdateras diagramdata från målarboken. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Extern arbetsbok är inte tillgänglig eller kan inte laddas. |



### See Also
* klass [`IChartData`](/slides/python-net/sv/aspose.slides.charts/ichartdata)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)