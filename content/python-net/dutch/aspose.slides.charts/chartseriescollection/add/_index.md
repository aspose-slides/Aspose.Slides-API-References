---
title: add method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
Maakt een nieuwe grafiekserie aan en voegt deze toe aan de verzameling.

### Retour

Nieuwe grafiekserie.



```python
def add(self, type):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/nl/aspose.slides.charts/charttype) | Type van serie |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Maakt een nieuwe grafiekserie aan van [`ChartDataCell`](/slides/python-net/nl/aspose.slides.charts/chartdatacell) en voegt deze toe aan de verzameling.

### Retour

Toegevoegde grafiekserie of serie die al in de verzameling aanwezig is.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/nl/aspose.slides.charts/ichartdatacell) | Cel die de serienaam bevat. |
| type | [`ChartType`](/slides/python-net/nl/aspose.slides.charts/charttype) | Type stelt het type van serie in |

### Opmerkingen

Als een grafiekserie die is aangemaakt uit dezelfde cel al in de verzameling zit, voegt de methode niets toe en retourneert de index.



## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Maakt een nieuwe grafiekserie aan van [`ChartCellCollection`](/slides/python-net/nl/aspose.slides.charts/chartcellcollection) en voegt deze toe aan de verzameling.

### Retour

Toegevoegde grafiekserie of serie die al in de verzameling aanwezig is.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcellcollection) | Cellen die de serienaam bevatten. |
| type | [`ChartType`](/slides/python-net/nl/aspose.slides.charts/charttype) | Type stelt het type van serie in |

### Opmerkingen

Als een grafiekserie die is aangemaakt uit dezelfde cel al in de verzameling zit, voegt de methode niets toe en retourneert de index.



## add(self, name, type) {#str-charttype}
Maakt een nieuwe grafiekserie aan van een waarde en voegt deze toe aan de verzameling.

### Retour

Toegevoegde grafiekserie.



```python
def add(self, name, type):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| name | **str** | Serienaam. |
| type | [`ChartType`](/slides/python-net/nl/aspose.slides.charts/charttype) | Type stelt het type van serie in |



### Zie ook
* klasse [`ChartCellCollection`](/slides/python-net/nl/aspose.slides.charts/chartcellcollection)
* klasse [`ChartDataCell`](/slides/python-net/nl/aspose.slides.charts/chartdatacell)
* klasse [`ChartSeriesCollection`](/slides/python-net/nl/aspose.slides.charts/chartseriescollection)
* enumeratie [`ChartType`](/slides/python-net/nl/aspose.slides.charts/charttype)
* klasse [`IChartCellCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcellcollection)
* klasse [`IChartDataCell`](/slides/python-net/nl/aspose.slides.charts/ichartdatacell)
* klasse [`IChartSeries`](/slides/python-net/nl/aspose.slides.charts/ichartseries)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)