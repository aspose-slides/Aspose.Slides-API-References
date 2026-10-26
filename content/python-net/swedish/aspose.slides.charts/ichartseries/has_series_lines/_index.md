---
title: has_series_lines property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartseries/has_series_lines/
weight: 180
---
## has_series_lines egenskap
Determinerar om det finns serielinjer för denna serie och besläktade serier.
            Detta är egenskapen inte bara för denna serie utan för alla serier i föräldra-serieggruppen 
            – detta är en projektion av lämplig grupp-egenskap. Och så är denna egenskap 
            skrivskyddad.
            Använd ParentSeriesGroup egenskap för åtkomst till föräldraseriesgruppen.
            Använd ParentSeriesGroup.HasSeriesLines läs/skriv egenskap för att ändra värdet.
            Använd ParentSeriesGroup.SeriesLinesFormat egenskap för att formatera serielinjer.
            Skrivskyddad **bool**.


### Anmärkningar

Detta är projektionen av egenskapen ParentSeriesGroup.HasSeriesLines.

### Definition:
```python
@property
def has_series_lines(self):
    ...
```


### Se även
* klass [`IChartSeries`](/slides/python-net/sv/aspose.slides.charts/ichartseries)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)