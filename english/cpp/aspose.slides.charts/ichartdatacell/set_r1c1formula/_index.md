---
title: set_R1C1Formula()
second_title: Aspose.Slides for C++ API Reference
description: Sets the formula in R1C1-style.
type: docs
weight: 92
url: /cpp/aspose.slides.charts/ichartdatacell/set_r1c1formula/
---
## IChartDataCell::set_R1C1Formula([System::String](../../../system/string/)) method


Sets the formula in R1C1-style.

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_R1C1Formula(System::String value)=0
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
