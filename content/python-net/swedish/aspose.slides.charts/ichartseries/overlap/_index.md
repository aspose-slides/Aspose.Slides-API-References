---
title: overlap property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartseries/overlap/
weight: 310
---
## överlappning egenskap
Anger hur mycket staplar och kolumner överlappar på 2-D-diagram, som en procentsats (från -100% till 100%).
Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade seriegruppen.
Den är en projektion av den motsvarande egenskapen i den överordnade seriegruppen, och därför är denna egenskap skrivskyddad.
För att ändra värdet, använd ParentSeriesGroup.Overlap läs/skriv egenskap.
Skrivskyddad **int**.

### Anmärkningar
Överlappning anger graden av överlappning eller avstånd mellan staplar och kolumner som en procentandel av deras bredd:
- -100%: Maximal avstånd (staplar är helt separerade).
- 0%: Staplar placeras sida vid sida utan överlappning eller avstånd.
- 100%: Maximal överlappning (staplar överlappar varandra helt).
Detta är en projektion av egenskapen ParentSeriesGroup.Overlap.

### Definition:
```python
@property
def overlap(self):
    ...
```

### Se även
* klass [`IChartSeries`](/slides/python-net/sv/aspose.slides.charts/ichartseries)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)