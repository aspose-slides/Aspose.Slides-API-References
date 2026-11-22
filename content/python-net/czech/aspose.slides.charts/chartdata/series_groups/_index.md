---
title: series_groups property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/chartdata/series_groups/
weight: 150
---
## series_groups vlastnost
Získá skupiny řad.
            Pouze pro čtení [`IChartSeriesGroupCollection`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroupcollection).


### Poznámky

1) Každá skupina řad obsahuje řady s kombinovatelnými typy. Skupiny kombinovatelných typů řad jsou definovány a popsány pomocí výčtu CombinableSeriesTypesGroup enum.
            Také každá skupina řad obsahuje řadu, která je vykreslena buď na primární ose, nebo na sekundární ose (nikoli v obou případech ve stejné skupině).
            Princip seskupování řad je tedy seskupování podle výše zmíněných typových skupin a podle typu vykreslení primární/sekundární.
            
            2) Skupina řad obsahuje některé vlastnosti řad, které jsou společné pro každou řadu ve skupině ("vlastnosti skupiny řad").
            "Vlastnosti skupiny řad" v třídě ChartSeriesGroup jsou čtení/zápis.
            Každá z "vlastností skupiny řad" může mít pouze pro čtení projekci v třídě ChartSeries.

### Definice:
```python
@property
def series_groups(self):
    ...
```


### Viz také
* třída [`ChartData`](/slides/python-net/cs/aspose.slides.charts/chartdata)
* třída [`IChartSeriesGroupCollection`](/slides/python-net/cs/aspose.slides.charts/ichartseriesgroupcollection)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)