---
title: show_label_value_from_cell property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/datalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell eigenschap
Stelt het weergavegedrag van de celwaarde van een gegevenslabel van een gespecificeerd diagram voor. 
            True toont celwaarde. False verbergt deze.
            Lezen/schrijven **bool**.


### Opmerkingen

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowLabelValueFromCell-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie.
            Het instellen van deze eigenschap met een waarde stelt deze waarde tevens in voor de ShowLabelValueFromCell-eigenschap van alle gegevenslabels in de DataLabelCollection-collectie
            (bijv. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" zorgt ervoor dat alle DataLabels[i].ShowLabelValueFromCell gelijk is aan val).

### Definitie:
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```


### Zie ook
* klasse [`DataLabelFormat`](/slides/python-net/nl/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)