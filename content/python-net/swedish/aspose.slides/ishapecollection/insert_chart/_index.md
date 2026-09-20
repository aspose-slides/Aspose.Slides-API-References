---
title: insert_chart method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ishapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar,
            och infogar det i shape-samlingen på det angivna indexet.

### Returnerar

Det nyss skapade [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/sv/aspose.slides.charts/charttype) | Typen av diagram som ska skapas. |
| x | **float** | X-koordinaten för det nya diagrammet, i punkter. |
| y | **float** | Y-koordinaten för det nya diagrammet, i punkter. |
| width | **float** | Bredden på det nya diagrammet, i punkter. |
| height | **float** | Höjden på det nya diagrammet, i punkter. |
| index | **int** | Det nollbaserade indexet där det nya diagrammet ska infogas i shape-samlingen. |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
Skapar ett nytt diagram, initierar det med exempelseriedata och inställningar,
            och infogar det i shape-samlingen på det angivna indexet.

### Returnerar

Det nyss skapade [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/sv/aspose.slides.charts/charttype) | Typen av diagram som ska skapas. |
| x | **float** | X-koordinaten för det nya diagrammet, i punkter. |
| y | **float** | Y-koordinaten för det nya diagrammet, i punkter. |
| width | **float** | Bredden på det nya diagrammet, i punkter. |
| height | **float** | Höjden på det nya diagrammet, i punkter. |
| index | **int** | Det nollbaserade indexet där det nya diagrammet ska infogas i shape-samlingen. |
| init_with_sample | **bool** | True för att initiera det nya diagrammet med exempelseriedata och inställningar; <br/><br/>            false för att skapa diagrammet utan serier och endast minimala inställningar, vilket gör skapandet snabbare. |



### Se även
* enumeration [`ChartType`](/slides/python-net/sv/aspose.slides.charts/charttype)
* klass [`IChart`](/slides/python-net/sv/aspose.slides.charts/ichart)
* klass [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)