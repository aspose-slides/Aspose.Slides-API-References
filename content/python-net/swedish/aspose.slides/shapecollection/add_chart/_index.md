---
title: add_chart method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/shapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och lägger till det i slutet av formsamlingen.

### Returnerar

Den nyss skapade [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/sv/aspose.slides.charts/charttype) | Typen av diagram att lägga till. |
| x | **float** | X-koordinaten för det nya diagrammet, i punkter. |
| y | **float** | Y-koordinaten för det nya diagrammet, i punkter. |
| width | **float** | Diagrammets bredd, i punkter. |
| height | **float** | Diagrammets höjd, i punkter. |


## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar, och lägger till det i slutet av formsamlingen.

### Returnerar

Den nyss skapade [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/sv/aspose.slides.charts/charttype) | Typen av diagram att lägga till. |
| x | **float** | X-koordinaten för det nya diagrammet, i punkter. |
| y | **float** | Y-koordinaten för det nya diagrammet, i punkter. |
| width | **float** | Diagrammets bredd, i punkter. |
| height | **float** | Diagrammets höjd, i punkter. |
| init_with_sample | **bool** | Sant för att initiera det nya diagrammet med exempelseriedata och inställningar; <br/><br/>            falskt för att skapa diagrammet utan serier och endast med minimala inställningar, vilket gör skapandet<br/><br/>            snabbare. |



### Se även
* enumeration [`ChartType`](/slides/python-net/sv/aspose.slides.charts/charttype)
* klass [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart)
* klass [`ShapeCollection`](/slides/python-net/sv/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)