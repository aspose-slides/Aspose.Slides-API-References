---
title: has_series_lines property
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/ichartseries/has_series_lines/
weight: 180
---
## has_series_lines propriété
Determines whether there are series lines for this series and kindred series.
            This is the property not only of this series but of all series of parent series 
            group - this is projection of appropriate group property. And so this property 
            is read-only.
            Use ParentSeriesGroup property for access to parent series group.
            Use ParentSeriesGroup.HasSeriesLines read/write property for change value.
            Use ParentSeriesGroup.SeriesLinesFormat property for format series lines.
            Read-only **bool**.

### Remarques

This is the projection of the property ParentSeriesGroup.HasSeriesLines.

### Définition:
```python
@property
def has_series_lines(self):
    ...
```

### Voir aussi
* classe [`IChartSeries`](/slides/python-net/fr/aspose.slides.charts/ichartseries)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)