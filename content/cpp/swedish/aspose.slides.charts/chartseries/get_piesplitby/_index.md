---
title: get_PieSplitBy()
second_title: Aspose.Slides för C++ API-referens
description: Anger hur man bestämmer vilka datapunkter som finns i den andra pajen eller stapeln i ett paj-i-paj- eller stapel-i-paj-diagram. Detta är en egenskap inte bara för denna serie utan för alla serier i den överordnade föräldraseriagruppen - detta är en projektion av den lämpliga gruppens egenskap. Därför är denna egenskap skrivskyddad. Använd ParentSeriesGroup egenskap för åtkomst till föräldraseriagruppen. Använd get_ParentSeriesGroup()->get(set)_PieSplitBy() läs/skriv egenskap för att ändra värdet. Skrivskyddad PieSplitType.
type: docs
weight: 755
url: /sv/aspose.slides.charts/chartseries/get_piesplitby/
---
## ChartSeries::get_PieSplitBy() metod

Anger hur man bestämmer vilka datapunkter som finns i den andra paj eller stapel på ett paj-i-paj eller stapel-i-paj diagram. Detta är egenskapen inte bara för denna serie utan för alla serier i den överordnade föräldraseriagruppen - detta är en projektion av gruppens egenskap. Och därför är denna egenskap skrivskyddad. Använd ParentSeriesGroup egenskap för åtkomst till föräldraseriagruppen. Använd [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() läs/skriv egenskap för att ändra värde. Skrivskyddad [PieSplitType](../../piesplittype/).

```cpp
PieSplitType Aspose::Slides::Charts::ChartSeries::get_PieSplitBy() override
```

## Anmärkningar

1) Detta är en projektion av egenskapen [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy(). 2) Om egenskapsvärdet är [PieSplitType::Custom](../../piesplittype/) kan du definiera anpassad delningsinformation med [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/) egenskap.

## Se även

* Enum [PieSplitType](../../piesplittype/)
* Klass [ChartSeries](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)