---
title: get_Formula()
second_title: Aspose.Slides for C++ API Reference
description: Gets the formula in A1-style.
type: docs
weight: 53
url: /cpp/aspose.slides.charts/ichartdatacell/get_formula/
---
## IChartDataCell::get_Formula() method


Gets the formula in A1-style.

```cpp
virtual System::String Aspose::Slides::Charts::IChartDataCell::get_Formula()=0
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
