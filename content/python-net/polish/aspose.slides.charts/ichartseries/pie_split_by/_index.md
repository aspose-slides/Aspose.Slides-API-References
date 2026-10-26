---
title: pie_split_by property
second_title: Aspose.Slides dla Pythona – dokumentacja API .NET
description: 
type: docs
url: /pl/aspose.slides.charts/ichartseries/pie_split_by/
weight: 340
---
## pie_split_by właściwość
Specifies how to determine which data points are in the second pie or bar 
            on a pie-of-pie or bar-of-pie chart.
            This is the właściwość not only of this series but of all series of parent series 
            group - this is projection of appropriate group właściwość. And so this 
            właściwość is only to odczytu.
            Use ParentSeriesGroup właściwość for access to parent series group.
            Use ParentSeriesGroup.PieSplitBy odczyt/zapis właściwość for change value.
            Only to odczytu [`PieSplitType`](/slides/python-net/pl/aspose.slides.charts/piesplittype).

### Uwagi

1) This is the projection of the właściwość ParentSeriesGroup.PieSplitBy.
2) If właściwość value is PieSplitType.Custom then you can define custom split 
            information with ParentSeriesGroup.PieSplitCustomPoints właściwość.

### Definicja:
```python
@property
def pie_split_by(self):
    ...
```

### Zobacz także
* klasa [`IChartSeries`](/slides/python-net/pl/aspose.slides.charts/ichartseries)
* enumeracja [`PieSplitType`](/slides/python-net/pl/aspose.slides.charts/piesplittype)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)