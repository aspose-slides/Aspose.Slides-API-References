---
title: show_series_name property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/datalabelformat/show_series_name/
weight: 190
---
## show_series_name eigenschap
Retourneert of stelt een Boolean in om het weergavegedrag van de serienaam voor de gegevenslabels op een diagram aan te geven. 
            True om de serienaam weer te geven. False om te verbergen.
            Lezen/schrijven **bool**.

### Opmerkingen

Als de bovenliggende instantie van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan
            krijgt deze eigenschap of stelt deze de standaardwaarde van de ShowSeriesName-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie.
            Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowSeriesName-eigenschap
            van alle gegevenslabels in de DataLabelCollection-collectie
            (bijvoorbeeld "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" waardoor
            alle DataLabels[i].ShowSeriesName gelijk is aan val).

### Definitie:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```

### Zie ook
* klasse [`DataLabelFormat`](/slides/python-net/nl/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)