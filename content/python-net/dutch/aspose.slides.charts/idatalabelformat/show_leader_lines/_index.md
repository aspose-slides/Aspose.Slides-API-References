---
title: show_leader_lines property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/idatalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines eigenschap
Stelt het weergavegedrag van de leader lines van een gegevenslabel van een opgegeven diagram voor. 
True geeft de leader lines weer. False om te verbergen.
Lezen/schrijven **bool**.

### Opmerkingen

Als de ouder van dit DataLabelFormat-object een DataLabelCollection-verzameling van gegevenslabels is, dan krijgt of stelt deze eigenschap de standaardwaarde van de ShowLeaderLines-eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-verzameling.  
Het instellen van deze eigenschap met een waarde stelt deze waarde ook in voor de ShowLeaderLines-eigenschap van alle gegevenslabels in de DataLabelCollection-verzameling  
(i.e. "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" zorgt ervoor dat alle DataLabels[i].ShowLeaderLines gelijk is aan val).

### Definitie:
```python
@property
def show_leader_lines(self):
    ...

@show_leader_lines.setter
def show_leader_lines(self, value):
    ...
```

### Zie ook
* klasse [`IDataLabelFormat`](/slides/python-net/nl/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)