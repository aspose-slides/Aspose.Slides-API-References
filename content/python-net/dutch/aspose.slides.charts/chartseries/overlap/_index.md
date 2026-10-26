---
title: overlap property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartseries/overlap/
weight: 310
---
## overlap eigenschap
Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%). 
            This is the property not only of this series but of all series of parent series group. 
            It is a projection of the appropriate property in the parent series group, and so this property is read-only.
            To change the value, use the **ParentSeriesGroup.Overlap** read/write property.
            Read-only **int**.

### Opmerkingen

Overlap specifies the degree of overlap or spacing between bars and columns as a percentage of their width:
            - -100%: Maximum spacing (bars are completely separated).
            - 0%: Bars are placed side by side without overlap or spacing.
            - 100%: Maximum overlap (bars completely overlap each other).
            This is a projection of the property **ParentSeriesGroup.Overlap**.

### Definitie:
```python
@property
def overlap(self):
    ...
```

### Zie ook
* klasse [`ChartSeries`](/slides/python-net/nl/aspose.slides.charts/chartseries)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)