---
title: set_Formula()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de formule in A1-stijl in.
type: docs
weight: 66
url: /nl/aspose.slides.charts/ichartdatacell/set_formula/
---
## IChartDataCell::set_Formula(System::String) methode

Stelt de formule in A1-stijl in.

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Formula(System::String value)=0
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