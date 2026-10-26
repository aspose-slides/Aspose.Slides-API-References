---
title: add method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/ichartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
Maakt een nieuwe grafiekserie aan en voegt deze toe aan de collectie.

### Retourwaarde

Nieuwe grafiekserie.



```python
def add(self, type):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/nl/aspose.slides.charts/charttype) | Type van serie |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Maakt een nieuwe grafiekserie aan vanuit [`IChartDataCell`](/slides/python-net/nl/aspose.slides.charts/ichartdatacell) en voegt deze toe aan de collectie.

### Retourwaarde

Toegevoegde grafiekserie of serie die al in de collectie aanwezig is.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/nl/aspose.slides.charts/ichartdatacell) | Cel die de serienaam bevat. |
| type | [`ChartType`](/slides/python-net/nl/aspose.slides.charts/charttype) | Type set type van serie |

### Opmerkingen

Als een grafiekserie die van dezelfde cel is aangemaakt al in de collectie aanwezig is, voegt de methode niets toe en retourneert zijn index.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Maakt een nieuwe grafiekserie aan vanuit [`IChartCellCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcellcollection) en voegt deze toe aan de collectie.

### Retourwaarde

Toegevoegde grafiekserie of serie die al in de collectie aanwezig is.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcellcollection) | Cellen die de serienaam bevatten. |
| type | [`ChartType`](/slides/python-net/nl/aspose.slides.charts/charttype) | Type set type van serie |

### Opmerkingen

Als een grafiekserie die van dezelfde cel is aangemaakt al in de collectie aanwezig is, voegt de methode niets toe en retourneert zijn index.


## add(self, name, type) {#str-charttype}
Maakt een nieuwe grafiekserie aan vanuit waarde en voegt deze toe aan de collectie.

### Retourwaarde

Toegevoegde grafiekserie.



```python
def add(self, name, type):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| name | **str** | Serienaam. |
| type | [`ChartType`](/slides/python-net/nl/aspose.slides.charts/charttype) | Type set type van serie |



### Zie ook
* enumeratie [`ChartType`](/slides/python-net/nl/aspose.slides.charts/charttype)
* klasse [`IChartCellCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcellcollection)
* klasse [`IChartDataCell`](/slides/python-net/nl/aspose.slides.charts/ichartdatacell)
* klasse [`IChartSeries`](/slides/python-net/nl/aspose.slides.charts/ichartseries)
* klasse [`IChartSeriesCollection`](/slides/python-net/nl/aspose.slides.charts/ichartseriescollection)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)