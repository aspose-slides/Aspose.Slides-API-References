---
title: show_leader_lines property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/datalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines egenskap
Representerar ett specificerat diagrams dataetikettledarlinjers visningsbeteende. 
True visar ledarlinjerna. False för att dölja.
Läs/skriv **bool**.

### Anmärkningar

Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så får eller sätter denna egenskap standardvärdet för ShowLeaderLines-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen. 
Att sätta denna egenskap med ett värde sätter även detta värde till ShowLeaderLines-egenskapen för alla dataetiketter i DataLabelCollection-samlingen (dvs. “DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;” medför att alla DataLabels[i].ShowLeaderLines är lika med val).

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
* klass [`DataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)