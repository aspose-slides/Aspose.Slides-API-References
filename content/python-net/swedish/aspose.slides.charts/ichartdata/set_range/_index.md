---
title: set_range method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
Ställ in diagrammets dataområde. Serie och kategorier uppdateras baserat på det nya dataområdet.
            Om antalet serier i dataområdet är större än antalet serier i diagrammets data läggs ytterligare serier med samma typ
            som den sista serien i den aktuella samlingen till i slutet av samlingen.


```python
def set_range(self, formula):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| formula | **str** | Formeln för cellernas dataområde. Till exempel: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula är None. |
| **RuntimeError(Proxy error(ArgumentException))** | formula har fel format. |



### Se även
* klass [`IChartData`](/slides/python-net/sv/aspose.slides.charts/ichartdata)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)