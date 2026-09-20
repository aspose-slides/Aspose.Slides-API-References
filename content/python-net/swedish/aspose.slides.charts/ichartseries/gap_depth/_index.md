---
title: gap_depth property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartseries/gap_depth/
weight: 160
---
## gap_depth egenskap
Returnerar eller anger avståndet, som en procentandel av markörens bredd, mellan dataserierna i ett 3D-diagram.
            Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade serieggruppen – detta är en projektion av lämplig gruppegenskap. Och därför är denna egenskap skrivskyddad.
            Använd egenskapen ParentSeriesGroup för åtkomst till den överordnade serieggruppen.
            Använd ParentSeriesGroup.GapDepth läs/skriv egenskap för att ändra värdet.
            Skrivskyddad **int**.


### Anmärkningar

Detta är projektionen av egenskapen ParentSeriesGroup.GapDepth.

### Definition:
```python
@property
def gap_depth(self):
    ...
```


### Se även
* klass [`IChartSeries`](/slides/python-net/sv/aspose.slides.charts/ichartseries)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)