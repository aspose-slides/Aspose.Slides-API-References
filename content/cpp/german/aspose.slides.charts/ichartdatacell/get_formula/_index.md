---
title: get_Formula()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Formel im A1-Stil zurück.
type: docs
weight: 53
url: /de/aspose.slides.charts/ichartdatacell/get_formula/
---
## IChartDataCell::get_Formula() Methode


Gibt die Formel im A1-Stil zurück.

```cpp
virtual System::String Aspose::Slides::Charts::IChartDataCell::get_Formula()=0
```

## Hinweise



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [IChartDataCell](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)