---
title: show_category_name property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/datalabelformat/show_category_name/
weight: 130
---
## show_category_name eigenschap
Stelt het weergavegedrag van de categorienaam van de gegevenslabels van een opgegeven diagram voor.
True om de categorienaam voor de gegevenslabels op een diagram weer te geven. False om te verbergen.
Lezen/schrijven **bool**.

### Opmerkingen

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan haalt deze eigenschap de standaardwaarde van de ShowCategoryName-eigenschap op of stelt deze in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie. Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowCategoryName-eigenschap van alle gegevenslabels in de DataLabelCollection-collectie (bijv. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" waardoor alle DataLabels[i].ShowCategoryName gelijk is aan val).

### Definitie:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```

### Zie ook
* klasse [`DataLabelFormat`](/slides/python-net/nl/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)