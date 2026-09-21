---
title: show_category_name property
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides.charts/idatalabelformat/show_category_name/
weight: 130
---
## show_category_name eigenschap
Geeft het weergavegedrag van de categorienaam van een data-label van een opgegeven diagram weer.
True om de categorienaam voor de data-labels op een diagram weer te geven. False om te verbergen.
Lezen/Schrijven **bool**.

### Opmerkingen

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van data-labels is, dan krijgt of stelt deze eigendom de standaardwaarde van de ShowCategoryName-eigenschap in voor de nieuwe data-labels in de DataLabelCollection-verzameling.
Het instellen van deze eigendom met een waarde stelt deze waarde ook in op de ShowCategoryName-eigenschap voor alle data-labels in de DataLabelCollection-verzameling
(bijvoorbeeld "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" zorgt ervoor dat alle DataLabels[i].ShowCategoryName gelijk is aan val).

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
* klasse [`IDataLabelFormat`](/slides/python-net/nl/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)