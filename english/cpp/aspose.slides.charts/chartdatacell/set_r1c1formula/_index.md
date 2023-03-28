---
title: set_R1C1Formula()
second_title: Aspose.Slides for C++ API Reference
description: Sets the formula in R1C1-style.
type: docs
weight: 92
url: /cpp/aspose.slides.charts/chartdatacell/set_r1c1formula/
---
## ChartDataCell::set_R1C1Formula([System::String](../../../system/string/)) method


Sets the formula in R1C1-style.

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_R1C1Formula(System::String value) override
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
