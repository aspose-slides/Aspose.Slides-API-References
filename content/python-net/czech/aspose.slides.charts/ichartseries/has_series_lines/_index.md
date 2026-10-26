---
title: has_series_lines property
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/ichartseries/has_series_lines/
weight: 180
---
## has_series_lines vlastnost
Určuje, zda pro tuto sérii a související série existují čáry sérií.
            Tato vlastnost není pouze této sérii, ale všem sériím skupiny nadřazených sérií – jedná se o projekci odpovídající vlastnosti skupiny. A proto je tato vlastnost pouze ke čtení.
            Použijte vlastnost ParentSeriesGroup pro přístup ke skupině nadřazených sérií.
            Použijte vlastnost ParentSeriesGroup.HasSeriesLines pro čtení a zápis k změně hodnoty.
            Použijte vlastnost ParentSeriesGroup.SeriesLinesFormat pro formát čar sérií.
            Pouze ke čtení **bool**.

### Poznámky

Jedná se o projekci vlastnosti ParentSeriesGroup.HasSeriesLines.

### Definice:
```python
@property
def has_series_lines(self):
    ...
```

### See Also
* třída [`IChartSeries`](/slides/python-net/cs/aspose.slides.charts/ichartseries)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)