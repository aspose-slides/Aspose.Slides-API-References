---
title: series_groups property
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/ichartdata/series_groups/
weight: 140
---
## series_groups property
Získá skupiny řad.
            Pouze pro čtení [`IChartSeriesGroupCollection`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroupcollection).

### Poznámky

1) Každá skupina řad obsahuje řady s kombinovatelnými typy. Skupiny
            kombinovatelných typů řad definované a popsány pomocí CombinableSeriesTypesGroup 
            enum.
            Také každá skupina řad obsahuje řady, které jsou vykresleny buď na hlavních osách nebo na sekundárních osách (ne v obou případech ve stejné skupině).
            Princip skupinování řad je tedy seskupování podle výše zmíněných typových skupin a podle typu vykreslování na hlavní/sekundární osu.

            2) Skupina řad obsahuje některé vlastnosti řad, které jsou společné pro každou řadu ve skupině ("series group properties").
            "Series group properties" v třídě ChartSeriesGroup je čtení/zápis.
            Každá z "series group properties" může mít pouze pro čtení projekci ve třídě ChartSeries.

### Definice:
```python
@property
def series_groups(self):
    ...
```

### Viz také
* třída [`IChartData`](/slides/python-net/cs/aspose.slides.charts/ichartdata)
* třída [`IChartSeriesGroupCollection`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroupcollection)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)