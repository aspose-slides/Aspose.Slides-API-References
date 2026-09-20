---
title: series_groups property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/chartdata/series_groups/
weight: 140
---
## series_groups egenskap
Hämtar grupperna av serier.
Skrivskyddad [`IChartSeriesGroupCollection`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroupcollection).

### Anmärkningar

1) Varje grupp av serier innehåller serier med kombinerbara typer. Grupper av kombinerbara serietyper definieras och beskrivs med CombinableSeriesTypesGroup enum.
   Dessutom innehåller varje grupp av serier serier som plottas antingen på primära axlar eller på sekundära axlar (inte båda fallen i en grupp).
   Så är principen för seriesammanslagning en gruppering enligt typgrupperna ovan och enligt primär/sekundär plottningstyp.

2) En grupp av serier innehåller vissa serieegenskaper som är gemensamma för varje serie i gruppen ("Seriegruppsegenskaper").
   "Seriegruppsegenskaper" i klassen ChartSeriesGroup är läs/skriv.
   Varje av "seriegruppsegenskaper" kan ha en skrivskyddad projektion i klassen ChartSeries.

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