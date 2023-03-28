---
title: set_Formula()
second_title: Aspose.Slides for C++ API Reference
description: Sets the formula in A1-style.
type: docs
weight: 66
url: /cpp/aspose.slides.charts/ichartdatacell/set_formula/
---
## IChartDataCell::set_Formula([System::String](../../../system/string/)) method


Sets the formula in A1-style.

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Formula(System::String value)=0
```

## Remarks



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## See Also

* Class [String](../../../system/string/)
* Class [IChartDataCell](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
