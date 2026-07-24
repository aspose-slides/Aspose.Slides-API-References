---
title: get_R1C1Formula()
second_title: Aspose.Slides für C++ API-Referenz
description: Liefert die Formel im R1C1-Stil.
type: docs
weight: 79
url: /de/aspose.slides.charts/chartdatacell/get_r1c1formula/
---
## ChartDataCell::get_R1C1Formula() Methode


Liefert die Formel im R1C1-Stil.

```cpp
System::String Aspose::Slides::Charts::ChartDataCell::get_R1C1Formula() override
```

## Anmerkungen



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [ChartDataCell](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)