---
title: add method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
Voeg een nieuwe cel toe aan de collectie.



```python
def add(self, cell):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/nl/aspose.slides.charts/ichartdatacell) | Nieuwe cel om toe te voegen. |


## add(self, value) {#any}
Maakt [`ChartDataCell`](/slides/python-net/nl/aspose.slides.charts/chartdatacell) van de opgegeven waarde en voegt deze toe aan de collectie.



```python
def add(self, value):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| value | **any** | De waarde. |

### Opmerkingen

Deze methode voegt een werkblad met de naam AUTO_DATA toe en voegt daar alle waarden toe. Als u [`ChartDataWorkbook`](/slides/python-net/nl/aspose.slides.charts/chartdataworkbook) gebruikt om celwaarden toe te voegen of te bewerken, zorg er dan voor dat u dit werkblad niet gebruikt
            Het maximale aantal waarden dat met deze methode wordt toegevoegd mag 16711680 niet overschrijden

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | als de limiet wordt overschreden |



### Zie ook
* klasse [`ChartCellCollection`](/slides/python-net/nl/aspose.slides.charts/chartcellcollection)
* klasse [`ChartDataCell`](/slides/python-net/nl/aspose.slides.charts/chartdatacell)
* klasse [`ChartDataWorkbook`](/slides/python-net/nl/aspose.slides.charts/chartdataworkbook)
* klasse [`IChartDataCell`](/slides/python-net/nl/aspose.slides.charts/ichartdatacell)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)