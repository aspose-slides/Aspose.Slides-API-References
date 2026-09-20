---
title: add_chart method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ishapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
Skapar ett nytt diagram, initierar det med exempelserie-data och inställningar, och lägger till det i slutet av formsamlingen.

### Returnerar

Det nyss skapade [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/sv/aspose.slides.charts/charttype) | Typen av diagram som ska läggas till. |
| x | **float** | X-koordinaten för det nya diagrammet, i punkter. |
| y | **float** | Y-koordinaten för det nya diagrammet, i punkter. |
| width | **float** | Diagrammets bredd, i punkter. |
| height | **float** | Diagrammets höjd, i punkter. |


## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
Skapar ett nytt diagram, initierar det med exempelserie-data och inställningar, och lägger till det i slutet av formsamlingen.

### Returnerar

Det nyss skapade [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/sv/aspose.slides.charts/charttype) | Typen av diagram som ska läggas till. |
| x | **float** | X-koordinaten för det nya diagrammet, i punkter. |
| y | **float** | Y-koordinaten för det nya diagrammet, i punkter. |
| width | **float** | Diagrammets bredd, i punkter. |
| height | **float** | Diagrammets höjd, i punkter. |
| init_with_sample | **bool** | True för att initiera det nya diagrammet med exempelserie-data och inställningar; <br/><br/>false för att skapa diagrammet utan serier och endast med minimal inställning, vilket gör skapandet snabbare. |



### Se även
* enumeration [`ChartType`](/slides/python-net/sv/aspose.slides.charts/charttype)
* class [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart)
* class [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)