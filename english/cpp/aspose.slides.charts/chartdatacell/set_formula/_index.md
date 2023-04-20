---
title: set_Formula()
second_title: Aspose.Slides for C++ API Reference
description: Sets the formula in A1-style.
type: docs
weight: 66
url: /cpp/aspose.slides.charts/chartdatacell/set_formula/
---
## ChartDataCell::set_Formula(System::String) method


Sets the formula in A1-style.

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Formula(System::String value) override
```

## Remarks



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## See Also

* Class [String](../../../system/string/)
* Class [ChartDataCell](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)