---
title: number_format property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/datalabelformat/number_format/
weight: 80
---
## number_format eigenschap
Stelt de opmaaktekenreeks voor het DataLabels-object voor.
            Lezen/schrijven **str**.


### Opmerkingen

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-collectie van datalabels is, dan haalt deze eigenschap op of stelt de standaardwaarde van de NumberFormat-eigenschap in voor de nieuwe datalabels in de DataLabelCollection-collectie. Wanneer deze eigenschap wordt ingesteld met een waarde, wordt die waarde ook ingesteld voor de NumberFormat-eigenschap voor alle datalabels in de DataLabelCollection-collectie (i.e. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" zorgt ervoor dat alle DataLabels[i].NumberFormat gelijk is aan val).

### Definitie:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```


### Zie ook
* klasse [`DataLabelFormat`](/slides/python-net/nl/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)