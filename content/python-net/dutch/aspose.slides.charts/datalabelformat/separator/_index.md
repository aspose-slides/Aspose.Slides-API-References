---
title: separator property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/datalabelformat/separator/
weight: 110
---
## separator eigenschap
Stelt een Variant in of retourneert deze, die de separator vertegenwoordigt die wordt gebruikt voor de data-labels op een diagram.
            Lezen/Schrijven **str**.


### Opmerkingen

Als de ouder van dit DataLabelFormat object een DataLabelCollection collectie van data-labels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de Separator property voor de nieuwe data-labels in de DataLabelCollection collectie.
            Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de Separator property voor alle data-labels in de DataLabelCollection collectie
            (bijv. "DataLabels.DefaultDataLabelFormat.Separator = val;" veroorzaakt dat alle DataLabels[i].Separator gelijk is aan val).

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
* klasse [`DataLabelFormat`](/slides/python-net/nl/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)