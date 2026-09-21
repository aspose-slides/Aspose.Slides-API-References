---
title: add method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Als de categorie bestaat in de collectie, retourneer deze. Anders maakt het een nieuwe grafiekcategorie aan van [`IChartDataCell`](/slides/python-net/nl/aspose.slides.charts/ichartdatacell) en voegt die toe aan de collectie.

### Retour
Toegevoegde of bestaande categorie.



```python
def add(self, chart_data_cell):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/nl/aspose.slides.charts/ichartdatacell) | Cel die wordt gebruikt om de grafiekcategorie te maken. |


## add(self, value) {#any}
Maakt een nieuwe [`ChartCategory`](/slides/python-net/nl/aspose.slides.charts/chartcategory) van de waarde en voegt deze toe aan de collectie.

### Retour
Toegevoegd [`IChartCategory`](/slides/python-net/nl/aspose.slides.charts/ichartcategory).



```python
def add(self, value):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| value | **any** | De waarde. |

### Opmerkingen
Deze methode voegt een werkblad met de naam AUTO_DATA toe en voegt daar alle waarden toe. Als je [`ChartDataWorkbook`](/slides/python-net/nl/aspose.slides.charts/chartdataworkbook) gebruikt om celwaarden toe te voegen of te bewerken, zorg er dan voor dat je dit werkblad niet gebruikt. Het maximale aantal waarden dat met deze methode kan worden toegevoegd mag 16711680 niet overschrijden.

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | als de limiet wordt overschreden |



### Zie ook
* klasse [`ChartCategory`](/slides/python-net/nl/aspose.slides.charts/chartcategory)
* klasse [`ChartCategoryCollection`](/slides/python-net/nl/aspose.slides.charts/chartcategorycollection)
* klasse [`ChartDataWorkbook`](/slides/python-net/nl/aspose.slides.charts/chartdataworkbook)
* klasse [`IChartCategory`](/slides/python-net/nl/aspose.slides.charts/ichartcategory)
* klasse [`IChartDataCell`](/slides/python-net/nl/aspose.slides.charts/ichartdatacell)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)