---
title: series_groups property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/chartdata/series_groups/
weight: 150
---
## series_groups egenskap
Hämtar grupperna av serier.
            Skrivskyddad [`IChartSeriesGroupCollection`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroupcollection).

### Anmärkningar

1) Varje grupp av serier innehåller serier med kombinerbara typer. Grupper av 
            kombinerbara serietyper definieras och beskrivs med CombinableSeriesTypesGroup 
            enum.
            Dessutom innehåller varje grupp av serier serier som plottas antingen 
            på primära axlar eller på sekundära axlar (inte båda fallen i en grupp).
            Så är principen för seriegroupering en gruppering efter typgrupperna som 
            nämns ovan och efter primär/sekundär plottningstyp.

2) En grupp av serier innehåller vissa serieegenskaper som är gemensamma för 
            varje serie i gruppen ("series group properties").
            "Series group properties" i ChartSeriesGroup klass är läs/skriv.
            Var och en av "Series group properties" kan ha en skrivskyddad projektion i ChartSeries klass.

### Definition:
```python
@property
def series_groups(self):
    ...
```

### Se även
* klass [`ChartData`](/slides/python-net/sv/aspose.slides.charts/chartdata)
* klass [`IChartSeriesGroupCollection`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroupcollection)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)