---
title: get_Formula()
second_title: مرجع API Aspose.Slides للغة C++
description: يحصل على الصيغة بنمط A1.
type: docs
weight: 53
url: /ar/aspose.slides.charts/chartdatacell/get_formula/
---
## ChartDataCell::get_Formula() طريقة


يسترجع الصيغة بنمط A1.

```cpp
System::String Aspose::Slides::Charts::ChartDataCell::get_Formula() override
```

## ملاحظات



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [ChartDataCell](../)
* نطاق [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)