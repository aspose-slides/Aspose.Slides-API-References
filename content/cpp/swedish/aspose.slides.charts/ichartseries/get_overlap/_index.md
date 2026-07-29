---
title: get_Overlap()
second_title: Aspose.Slides för C++ API-referens
description: Anger hur mycket staplar och kolumner överlappar i 2-D diagram, som en procentandel (från -100% till 100%). Detta är en egenskap som inte bara gäller för denna serie utan för alla serier i föräldraserieggruppen. Det är en projektion av den motsvarande egenskapen i föräldraserieggruppen, och därför är denna egenskap skrivskyddad. För att ändra värdet, använd get_ParentSeriesGroup()->get(set)_Overlap() läs/skriv egenskap. Skrivskyddad int8_t.
type: docs
weight: 690
url: /sv/aspose.slides.charts/ichartseries/get_overlap/
---
## IChartSeries::get_Overlap() metod

Anger hur mycket staplar och kolumner överlappar på 2-D-diagram, som en procentandel (från -100% till 100%). Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade serieggruppen. Det är en projektion av motsvarande egenskap i den överordnade serieggruppen, och därför är denna egenskap skrivskyddad. För att ändra värdet, använd [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap() läs-/skriv-egenskap. Skrivskyddad **int8_t**.

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeries::get_Overlap()=0
```

## Anmärkningar

Överlappning anger graden av överlappning eller mellanrum mellan staplar och kolumner som en procentandel av deras bredd:
* -100%: Maximal avstånd (staplar är helt separerade).
* 0%: Staplar placeras sida vid sida utan överlappning eller mellanrum.
* 100%: Maximal överlappning (staplar överlappar varandra helt). Detta är en projektion av egenskapen [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_Overlap().

## Se även

* Klass [IChartSeries](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)