---
title: set_Formula()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de formule in A1-stijl in.
type: docs
weight: 66
url: /nl/aspose.slides.charts/chartdatacell/set_formula/
---
## ChartDataCell::set_Formula(System::String) methode


Stelt de formule in A1-stijl in.

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Formula(System::String value) override
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