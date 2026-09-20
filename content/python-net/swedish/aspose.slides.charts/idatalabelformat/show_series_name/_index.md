---
title: show_series_name property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/idatalabelformat/show_series_name/
weight: 190
---
## show_series_name egenskap
Returnerar eller anger ett Boolean för att indikera hur serienamnet ska visas för dataetiketterna i ett diagram. 
True för att visa serienamnet. False för att dölja.
Läs/skriv **bool**.

### Anmärkningar

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger denna egenskap standardvärdet för ShowSeriesName-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen.
Att sätta denna egenskap med ett värde sätter även detta värde till ShowSeriesName-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" gör att alla DataLabels[i].ShowSeriesName blir lika med val).

### Definition:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```

### Se även
* klass [`IDataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)