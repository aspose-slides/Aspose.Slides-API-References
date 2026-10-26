---
title: get_PieSplitBy()
second_title: Aspose.Slides för C++ API-referens
description: Anger hur man bestämmer vilka datapunkter som finns i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade serieggruppen - detta är en projektion av den lämpliga gruppens egenskap. Därför är denna egenskap skrivskyddad. Använd egenskapen ParentSeriesGroup för åtkomst till den överordnade serieggruppen. Använd get_ParentSeriesGroup()->get(set)_PieSplitBy() läs/skriv-egenskap för att ändra värdet. Läs-skyddad PieSplitType.
type: docs
weight: 729
url: /sv/aspose.slides.charts/ichartseries/get_piesplitby/
---
## IChartSeries::get_PieSplitBy() metod

Anger hur man bestämmer vilka datapunkter som finns i den andra pajen eller stapeln i ett pie-of-pie eller bar-of-pie diagram. Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade serieggruppen - detta är en projektion av den lämpliga gruppens egenskap. Därför är denna egenskap skrivskyddad. Använd egenskapen ParentSeriesGroup för åtkomst till den överordnade serieggruppen. Använd [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() läs/skriv egenskap för att ändra värdet. Läs-skyddad [PieSplitType](../../piesplittype/).

```cpp
virtual PieSplitType Aspose::Slides::Charts::IChartSeries::get_PieSplitBy()=0
```

## Anmärkningar

1) Detta är projektionen av egenskapen [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) Om egenskapsvärdet är [PieSplitType::Custom](../../piesplittype/) kan du definiera anpassad split-information med egenskapen [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/).

## Se även

* Enum [PieSplitType](../../piesplittype/)
* Klass [IChartSeries](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)