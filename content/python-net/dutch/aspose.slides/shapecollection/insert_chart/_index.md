---
title: insert_chart method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/shapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
Maakt een nieuw diagram, initialiseert het met voorbeeldreeksgegevens en instellingen,
            en voegt het in de vormverzameling in op de opgegeven index.

### Retourwaarde

Het nieuw aangemaakte [`IChart`](/slides/python-net/nl/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/nl/aspose.slides.charts/charttype) | Het type diagram om te maken. |
| x | **float** | De x-coördinaat van het nieuwe diagram, in punten. |
| y | **float** | De y-coördinaat van het nieuwe diagram, in punten. |
| width | **float** | De breedte van het nieuwe diagram, in punten. |
| height | **float** | De hoogte van het nieuwe diagram, in punten. |
| index | **int** | De nulgebaseerde index waarop het nieuwe diagram in de vormverzameling moet worden ingevoegd. |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
Maakt een nieuw diagram, initialiseert het met voorbeeldreeksgegevens en instellingen,
            en voegt het in de vormverzameling in op de opgegeven index.

### Retourwaarde

Het nieuw aangemaakte [`IChart`](/slides/python-net/nl/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/nl/aspose.slides.charts/charttype) | Het type diagram om te maken. |
| x | **float** | De x-coördinaat van het nieuwe diagram, in punten. |
| y | **float** | De y-coördinaat van het nieuwe diagram, in punten. |
| width | **float** | De breedte van het nieuwe diagram, in punten. |
| height | **float** | De hoogte van het nieuwe diagram, in punten. |
| index | **int** | De nulgebaseerde index waarop het nieuwe diagram in de vormverzameling moet worden ingevoegd. |
| init_with_sample | **bool** | True om het nieuwe diagram te initialiseren met voorbeeldreeksgegevens en instellingen; <br/><br/>false om het diagram te maken zonder reeksen en alleen met minimale instellingen, waardoor de creatie sneller gaat. |



### Zie ook
* enumeratie [`ChartType`](/slides/python-net/nl/aspose.slides.charts/charttype)
* klasse [`IChart`](/slides/python-net/nl/aspose.slides.charts/ichart)
* klasse [`ShapeCollection`](/slides/python-net/nl/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)