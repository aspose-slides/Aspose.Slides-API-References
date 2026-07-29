---
title: set_Formula()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in formeln i A1-stil.
type: docs
weight: 66
url: /sv/aspose.slides.charts/ichartdatacell/set_formula/
---
## IChartDataCell::set_Formula(System::String) metod


Ställer in formeln i A1-stil.

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Formula(System::String value)=0
```

## Anmärkningar



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Se även

* Klass [String](../../../system/string/)
* Klass [IChartDataCell](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)