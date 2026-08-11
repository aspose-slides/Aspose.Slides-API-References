---
title: get_Formula()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يحصل على الصيغة بنمط A1.
type: docs
weight: 53
url: /ar/aspose.slides.charts/ichartdatacell/get_formula/
---
## IChartDataCell::get_Formula() طريقة


يحصل على الصيغة بنمط A1.

```cpp
virtual System::String Aspose::Slides::Charts::IChartDataCell::get_Formula()=0
```

## ملاحظات



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [IChartDataCell](../)
* نطاق الاسم [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)