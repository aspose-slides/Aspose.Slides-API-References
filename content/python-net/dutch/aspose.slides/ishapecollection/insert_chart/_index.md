---
title: insert_chart method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ishapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
Maakt een nieuwe chart, initialiseert deze met voorbeeldreeksgegevens en instellingen,
            en voegt deze toe aan de shape-collectie op de opgegeven index.

### Retour

De nieuw aangemaakte [`IChart`](/slides/python-net/nl/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```



| Parameter | Type | Beschrijving |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/nl/aspose.slides.charts/charttype) | Het type van chart om te maken. |
| x | **float** | De x-coördinaat van de nieuwe chart, in punten. |
| y | **float** | De y-coördinaat van de nieuwe chart, in punten. |
| width | **float** | De breedte van de nieuwe chart, in punten. |
| height | **float** | De hoogte van de nieuwe chart, in punten. |
| index | **int** | De nulgebaseerde index waarop de nieuwe chart in de shape-collectie moet worden ingevoegd. |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
Maakt een nieuwe chart, initialiseert deze met voorbeeldreeksgegevens en instellingen,
            en voegt deze toe aan de shape-collectie op de opgegeven index.

### Retour

De nieuw aangemaakte [`IChart`](/slides/python-net/nl/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/nl/aspose.slides.charts/charttype) | Het type van chart om te maken. |
| x | **float** | De x-coördinaat van de nieuwe chart, in punten. |
| y | **float** | De y-coördinaat van de nieuwe chart, in punten. |
| width | **float** | De breedte van de nieuwe chart, in punten. |
| height | **float** | De hoogte van de nieuwe chart, in punten. |
| index | **int** | De nulgebaseerde index waarop de nieuwe chart in de shape-collectie moet worden ingevoegd. |
| init_with_sample | **bool** | True om de nieuwe chart te initialiseren met voorbeeldreeksgegevens en instellingen; false om de chart te maken zonder series en alleen minimale instellingen, wat de creatie versnelt. |



### Zie ook
* enumeration [`ChartType`](/slides/python-net/nl/aspose.slides.charts/charttype)
* class [`IChart`](/slides/python-net/nl/aspose.slides.charts/ichart)
* class [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)