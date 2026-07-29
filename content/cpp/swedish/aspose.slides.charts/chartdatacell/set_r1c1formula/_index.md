---
title: set_R1C1Formula()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in formeln i R1C1-stil.
type: docs
weight: 92
url: /sv/aspose.slides.charts/chartdatacell/set_r1c1formula/
---
## ChartDataCell::set_R1C1Formula(System::String) metod


Ställer in formeln i R1C1-style.

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_R1C1Formula(System::String value) override
```

## Anmärkningar



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## Se även

* Klass [String](../../../system/string/)
* Klass [ChartDataCell](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)