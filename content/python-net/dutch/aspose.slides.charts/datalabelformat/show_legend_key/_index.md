---
title: show_legend_key property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/datalabelformat/show_legend_key/
weight: 170
---
## show_legend_key eigenschap
Stelt het weergeven van de legende-sleutel van een gegevenslabel van een opgegeven diagram voor. 
            Waar als de legende-sleutel van het gegevenslabel zichtbaar is.
            Lezen/Schrijven **bool**.

### Opmerkingen
Als de bovenliggende van dit DataLabelFormat-object een DataLabelCollection-collectie van gegevenslabels is, dan krijgt deze eigenschap of stelt hij de standaardwaarde van de ShowLegendKey eigenschap in voor de nieuwe gegevenslabels in de DataLabelCollection-collectie.
            Het instellen van deze eigenschap met een waarde stelt deze waarde ook in op de ShowLegendKey eigenschap voor alle gegevenslabels in de DataLabelCollection-collectie
            (bijv. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" zorgt ervoor dat alle DataLabels[i].ShowLegendKey gelijk is aan val).

### Definitie:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```

### Zie ook
* klasse [`DataLabelFormat`](/slides/python-net/nl/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)