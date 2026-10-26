---
title: show_value property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/datalabelformat/show_value/
weight: 200
---
## show_value eigenschap
Stelt het weergavegedrag van het percentage van een gegevenslabel van een opgegeven diagram voor. 
            True toont de percentagewaarde. False om te verbergen.
            Lezen/Schrijven **bool**.


### Opmerkingen

Als de ouder van dit DataLabelFormat object een DataLabelCollection-verzameling van gegevenslabels is, dan krijgt deze
            eigenschap of stelt hij de standaardwaarde van de ShowValue Property in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling.
            Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowValue eigenschap 
            voor alle gegevenslabels in de DataLabelCollection-verzameling
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" veroorzaakt dat 
            alle DataLabels[i].ShowValue gelijk is aan val).

### Definitie:
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```


### Zie ook
* klasse [`DataLabelFormat`](/slides/python-net/nl/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)