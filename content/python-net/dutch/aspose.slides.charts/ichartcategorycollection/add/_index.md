---
title: add method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/ichartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Als de categorie bestaat in de collectie, retourneer deze. Anders maakt het een nieuwe grafiekcategorie aan vanuit [`IChartDataCell`](/slides/python-net/nl/aspose.slides.charts/ichartdatacell) en voegt deze toe aan de collectie.

### Retour

Toegevoegde of bestaande categorie.

```python
def add(self, chart_data_cell):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/nl/aspose.slides.charts/ichartdatacell) | Cel gebruikt om een grafiekcategorie te maken. |

## add(self, value) {#any}
Maakt een nieuw [`IChartCategory`](/slides/python-net/nl/aspose.slides.charts/ichartcategory) aan vanuit waarde en voegt het toe aan de collectie.

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

Deze methode voegt een werkblad met de naam AUTO_DATA toe en voegt daar alle waarden toe.  Als je [`IChartDataWorkbook`](/slides/python-net/nl/aspose.slides.charts/ichartdataworkbook) gebruikt om celwaarden toe te voegen of te bewerken, zorg er dan voor dat je dit werkblad niet gebruikt
            Het maximale aantal waarden dat met deze methode wordt toegevoegd mag 16711680 niet overschrijden

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | indien limiet overschreden |

### Zie ook
* klasse [`IChartCategory`](/slides/python-net/nl/aspose.slides.charts/ichartcategory)
* klasse [`IChartCategoryCollection`](/slides/python-net/nl/aspose.slides.charts/ichartcategorycollection)
* klasse [`IChartDataCell`](/slides/python-net/nl/aspose.slides.charts/ichartdatacell)
* klasse [`IChartDataWorkbook`](/slides/python-net/nl/aspose.slides.charts/ichartdataworkbook)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)