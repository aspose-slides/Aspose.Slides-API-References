---
title: series_groups property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartdata/series_groups/
weight: 140
---
## series_groups egenskap
Hämtar grupperna av serier.
            Skrivskyddad [`IChartSeriesGroupCollection`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroupcollection).

### Anmärkningar

1) Varje grupp av serier innehåller serier med kombinerbara typer. Grupper av kombinerbara serietyper definieras och beskrivs med enum CombinableSeriesTypesGroup. Dessutom innehåller varje grupp av serier serier som plottas antingen på primära axlar eller på sekundära axlar (inte båda fallen i en grupp). Således är principen för seriegruppering en gruppering efter typgrupperna som nämns ovan samt efter primär/sekundär plottningstyp.

2) En grupp av serier innehåller några serieegenskaper som är gemensamma för varje serie i gruppen ("Series group properties"). "Series group properties" i ChartSeriesGroup klass är läs/skriv. Varje av "Series group properties" kan ha en skrivskyddad projektion i ChartSeries klass.

### Definition:
```python
@property
def series_groups(self):
    ...
```

### Se även
* klass [`IChartData`](/slides/python-net/sv/aspose.slides.charts/ichartdata)
* klass [`IChartSeriesGroupCollection`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroupcollection)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)