---
title: get_R1C1Formula()
second_title: Aspose.Slides for C++ API Reference
description: Gets the formula in R1C1-style.
type: docs
weight: 79
url: /cpp/aspose.slides.charts/ichartdatacell/get_r1c1formula/
---
## IChartDataCell::get_R1C1Formula() method


Gets the formula in R1C1-style.

```cpp
virtual System::String Aspose::Slides::Charts::IChartDataCell::get_R1C1Formula()=0
```

## Remarks



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## See Also

* Class [String](../../../system/string/)
* Class [IChartDataCell](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
