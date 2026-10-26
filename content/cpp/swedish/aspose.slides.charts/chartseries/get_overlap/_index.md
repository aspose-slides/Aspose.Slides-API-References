---
title: get_Overlap()
second_title: Aspose.Slides för C++ API-referens
description: Anger hur mycket staplar och kolumner överlappar på 2-D-diagram, som en procentandel (från -100% till 100%). Detta är egenskapen inte bara för denna serie utan för alla serier i föräldra serieggruppen. Det är en projektion av den lämpliga egenskapen i föräldra serieggruppen, och därför är denna egenskap skrivskyddad. För att ändra värdet, använd get_ParentSeriesGroup()->Overlap() läs/skriv-egenskap. Skrivskyddad int8_t.
type: docs
weight: 690
url: /sv/aspose.slides.charts/chartseries/get_overlap/
---
## ChartSeries::get_Overlap() metod


Anger hur mycket staplar och kolumner överlappar på 2-D diagram, som en procentandel (från -100% till 100%). Detta är egenskapen inte bara för denna serie utan för alla serier i föräldra serieggruppen. Det är en projektion av den motsvarande egenskapen i föräldra serieggruppen, och därför är denna egenskap skrivskyddad. För att ändra värdet, använd [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/) läs/skriv-egenskap. Skrivskyddad **int8_t**.

```cpp
int8_t Aspose::Slides::Charts::ChartSeries::get_Overlap() override
```

## Anmärkningar


Överlappning anger graden av överlappning eller avstånd mellan staplar och kolumner som en procentandel av deras bredd:
* -100%: Maximalt avstånd (staplar är helt separerade).
* 0%: Staplar placeras sida vid sida utan överlappning eller avstånd.
* 100%: Maximal överlappning (staplar överlappar varandra helt). Detta är en projektion av egenskapen [get_ParentSeriesGroup()->Overlap()](../get_parentseriesgroup/).


## Se även

* Klass [ChartSeries](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)