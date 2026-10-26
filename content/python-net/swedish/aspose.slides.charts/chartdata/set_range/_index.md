---
title: set_range method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/chartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
Ange diagrammets dataintervall. Serie- och kategoriuppgifter kommer att uppdateras baserat på det nya dataintervallet.
            Om antalet serier i dataintervallet är större än antalet serier i diagrammets data, läggs ytterligare serier med samma typ som den sista serien i den nuvarande samlingen till i slutet av samlingen.


```python
def set_range(self, formula):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| formula | **str** | Formeln för cellernas dataområde. T.ex: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula är None. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Ej stödd diagramtyp |
| **RuntimeError(Proxy error(ArgumentException))** | formula har felaktigt format. |



### Se även
* klass [`ChartData`](/slides/python-net/sv/aspose.slides.charts/chartdata)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)