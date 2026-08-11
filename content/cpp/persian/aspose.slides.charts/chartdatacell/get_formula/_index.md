---
title: get_Formula()
second_title: مرجع API Aspose.Slides برای C++
description: فرمول را به سبک A1 دریافت می‌کند.
type: docs
weight: 53
url: /fa/aspose.slides.charts/chartdatacell/get_formula/
---
## ChartDataCell::get_Formula() متد


فرمول را به سبک A1 دریافت می‌کند.

```cpp
System::String Aspose::Slides::Charts::ChartDataCell::get_Formula() override
```

## توضیحات



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [ChartDataCell](../)
* فضای‌نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)