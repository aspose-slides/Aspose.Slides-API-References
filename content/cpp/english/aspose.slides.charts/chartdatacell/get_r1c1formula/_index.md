---
title: get_R1C1Formula()
second_title: Aspose.Slides for C++ API Reference
description: Gets the formula in R1C1-style.
type: docs
weight: 79
url: /aspose.slides.charts/chartdatacell/get_r1c1formula/
---
## ChartDataCell::get_R1C1Formula() method


Gets the formula in R1C1-style.

```cpp
System::String Aspose::Slides::Charts::ChartDataCell::get_R1C1Formula() override
```

## Remarks



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## See Also

* Class [String](../../../system/string/)
* Class [ChartDataCell](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)