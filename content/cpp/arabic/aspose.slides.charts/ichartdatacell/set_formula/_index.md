---
title: set_Formula()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد الصيغة بنمط A1.
type: docs
weight: 66
url: /ar/aspose.slides.charts/ichartdatacell/set_formula/
---
## IChartDataCell::set_Formula(System::String) طريقة


يحدد الصيغة بنمط A1.

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Formula(System::String value)=0
```

## ملاحظات



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [IChartDataCell](../)
* نطاق [Aspose::Slides::Charts](../../)
* المكتبة [Aspose.Slides](../../../)