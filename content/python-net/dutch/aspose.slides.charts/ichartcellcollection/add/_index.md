---
title: add method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Voeg een nieuwe cel toe aan de collectie.

```python
def add(self, chart_data_cell):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/nl/aspose.slides.charts/ichartdatacell) | Nieuwe cel om toe te voegen. |

## add(self, value) {#any}
Maakt [`IChartDataCell`](/slides/python-net/nl/aspose.slides.charts/ichartdatacell) van de opgegeven waarde en voegt het toe aan de collectie.

```python
def add(self, value):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| value | **any** | De waarde. |

### Opmerkingen
Deze methode voegt een werkblad met de naam AUTO_DATA toe en voegt daar alle waarden toe. Als je [`IChartDataWorkbook`](/slides/python-net/nl/aspose.slides.charts/ichartdataworkbook) gebruikt om Cel-waarden toe te voegen of te bewerken, zorg er dan voor dat je dit werkblad niet gebruikt.
Maximum aantal waarden dat met deze methode wordt toegevoegd mag niet meer dan 16711680 bedragen.

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | als limiet overschreden |

### Zie ook
* klasse [`IChartCellCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcellcollection)
* klasse [`IChartDataCell`](/slides/python-net/nl/aspose.slides.charts/ichartdatacell)
* klasse [`IChartDataWorkbook`](/slides/python-net/nl/aspose.slides.charts/ichartdataworkbook)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)