---
title: show_leader_lines property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/idatalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines egenskap
Representerar ett specificerat diagrammets dataetikettledarlinjers visningsbeteende. 
True visar ledarlinjerna. False döljer dem.
Läs/skriv **bool**.


### Anmärkningar

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så hämtar eller anger den här egenskapen standardvärdet för ShowLeaderLines-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. Att sätta den här egenskapen med ett värde sätter också detta värde på ShowLeaderLines-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (t.ex. "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" vilket gör att alla DataLabels[i].ShowLeaderLines är lika med val).

### Definition:
```python
@property
def show_leader_lines(self):
    ...

@show_leader_lines.setter
def show_leader_lines(self, value):
    ...
```


### Se även
* klass [`IDataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)