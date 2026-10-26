---
title: set_Formula()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt die Formel im A1-Stil.
type: docs
weight: 66
url: /de/aspose.slides.charts/chartdatacell/set_formula/
---
## ChartDataCell::set_Formula(System::String) Methode


Setzt die Formel im A1-Stil.

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Formula(System::String value) override
```

## Anmerkungen



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [ChartDataCell](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)