---
title: show_series_name property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/idatalabelformat/show_series_name/
weight: 190
---
## show_series_name eigenschap
Geeft een Boolean terug of stelt deze in om het weergeven van de serienaam voor de gegevenslabels op een diagram aan te geven. 
            True om de serienaam weer te geven. False om te verbergen.
            Lezen/schrijven **bool**.


### Opmerkingen

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan krijgt deze
            eigenschap of stelt deze de standaardwaarde van de ShowSeriesName-eigenschap in voor de nieuwe gegevens-
            labels in de DataLabelCollection-verzameling.
            Het instellen van deze eigenschap met een waarde stelt deze ook in voor de ShowSeriesName-eigenschap 
            voor alle gegevenslabels in de DataLabelCollection-verzameling
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" veroorzaakt dat 
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
* klasse [`IDataLabelFormat`](/slides/python-net/nl/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)