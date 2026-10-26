---
title: get_Formula()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de formule op in A1-stijl.
type: docs
weight: 53
url: /nl/aspose.slides.charts/chartdatacell/get_formula/
---
## ChartDataCell::get_Formula() methode


Haalt de formule op in A1-stijl.

```cpp
System::String Aspose::Slides::Charts::ChartDataCell::get_Formula() override
```

## Opmerkingen



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [ChartDataCell](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)