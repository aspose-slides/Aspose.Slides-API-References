---
title: overlap property
second_title: Aspose.Slides για Python μέσω .NET αναφορά API
description: 
type: docs
url: /el/aspose.slides.charts/ichartseries/overlap/
weight: 310
---
## ιδιότητα overlap
Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%). 
            This is the property not only of this series but of all series of parent series group. 
            It is a projection of the appropriate property in the parent series group, and so this property is read-only.
            To change the value, use the ParentSeriesGroup.Overlap read/write property.
            Μόνο για ανάγνωση **int**.


### Σχόλια

Overlap specifies the degree of overlap or spacing between bars and columns as a percentage of their width:
            - -100%: Maximum spacing (bars are completely separated).
            - 0%: Bars are placed side by side without overlap or spacing.
            - 100%: Maximum overlap (bars completely overlap each other).
            This is a projection of the property ParentSeriesGroup.Overlap.

### Ορισμός:
```python
@property
def overlap(self):
    ...
```


### Βλέπε επίσης
* κλάση [`IChartSeries`](/slides/python-net/el/aspose.slides.charts/ichartseries)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)