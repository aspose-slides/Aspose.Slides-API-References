---
title: separator property
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides.charts/idatalabelformat/separator/
weight: 110
---
## separator-eigenschap
Stelt een Variant in of geeft deze terug die de separator weergeeft die wordt gebruikt voor de data-labels op een chart.
            Lezen/schrijven **str**.


### Opmerkingen

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-collectie van data-labels is, krijgt deze eigenschap of stelt hij de standaardwaarde van de Separator-eigenschap in voor de nieuwe data-labels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de Separator-eigenschap van alle data-labels in de DataLabelCollection-collectie (bijv. "DataLabels.DefaultDataLabelFormat.Separator = val;" zorgt ervoor dat alle DataLabels[i].Separator gelijk is aan val).

### Definitie:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```


### Zie ook
* klasse [`IDataLabelFormat`](/slides/python-net/nl/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)