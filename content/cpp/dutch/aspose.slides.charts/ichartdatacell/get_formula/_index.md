---
title: get_Formula()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de formule op in A1-stijl.
type: docs
weight: 53
url: /nl/aspose.slides.charts/ichartdatacell/get_formula/
---
## IChartDataCell::get_Formula() methode

Haalt de formule op in A1-stijl.

```cpp
virtual System::String Aspose::Slides::Charts::IChartDataCell::get_Formula()=0
```

## Opmerkingen



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [IChartDataCell](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)