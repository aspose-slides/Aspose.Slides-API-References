---
title: overlap property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/chartseries/overlap/
weight: 310
---
## överlappning egenskap
Specifies how much bars and columns overlap on 2-D charts, as a percentage (from -100% to 100%). 
            Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade serieggruppen. 
            Den är en projektion av den lämpliga egenskapen i den överordnade serieggruppen, och därför är denna egenskap skrivskyddad.
            För att ändra värdet, använd den **ParentSeriesGroup.Overlap** läs/skriv egenskapen.
            Skrivskyddad **int**.


### Anmärkningar

Överlappning anger graden av överlappning eller avstånd mellan staplar och kolumner som en procent av deras bredd:
            - -100%: Maximalt avstånd (staplar är helt separerade).
            - 0%: Staplar placeras sida vid sida utan överlappning eller avstånd.
            - 100%: Maximal överlappning (staplar överlappar varandra helt).
            Detta är en projektion av egenskapen **ParentSeriesGroup.Overlap**.

### Definition:
```python
@property
def overlap(self):
    ...
```


### Se också
* klass [`ChartSeries`](/slides/python-net/sv/aspose.slides.charts/chartseries)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)