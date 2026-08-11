---
title: set_Formula()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضبط الصيغة بنمط A1.
type: docs
weight: 66
url: /ar/aspose.slides.charts/chartdatacell/set_formula/
---
## ChartDataCell::set_Formula(System::String) طريقة


يضبط الصيغة بنمط A1.

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Formula(System::String value) override
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