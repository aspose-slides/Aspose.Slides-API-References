---
title: show_label_value_from_cell property
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides.charts/idatalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell eigenschap
Geeft het weergavegedrag van de celwaarde van gegevenslabels van een opgegeven diagram weer. 
True toont de celwaarde. False verbergt deze.  
Lezen/Schrijven **bool**.

### Opmerkingen

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan verkrijgt of stelt deze eigenschap de standaardwaarde van de ShowLabelValueFromCell-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling.  
Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowLabelValueFromCell-eigenschap van alle gegevenslabels in de DataLabelCollection-verzameling  
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
* klasse [`IDataLabelFormat`](/slides/python-net/nl/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)