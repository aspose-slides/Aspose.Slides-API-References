---
title: show_bubble_size property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/datalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size eigenschap
Stelt het weergavegedrag van de bubbelgroottewaarde van een opgegeven diagram voor. 
            True geeft de bubbelgroottewaarde weer. False verbergen.
            Lezen/Schrijven **bool**.

### Opmerkingen

Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan haalt deze
            eigenschap de standaardwaarde van de ShowBubbleSize-eigenschap op of stelt deze in voor de nieuwe
            gegevenslabels in de DataLabelCollection-collectie.
            Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de ShowBubbleSize-eigenschap
            voor alle gegevenslabels in de DataLabelCollection-collectie
            (bijv. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" zorgt ervoor dat
            alle DataLabels[i].ShowBubbleSize gelijk is aan val).

### Definitie:
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```

### Zie ook
* klasse [`DataLabelFormat`](/slides/python-net/nl/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)