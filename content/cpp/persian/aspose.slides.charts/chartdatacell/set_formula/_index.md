---
title: set_Formula()
second_title: Aspose.Slides برای مرجع API C++
description: فرمول را به سبک A1 تنظیم می‌کند.
type: docs
weight: 66
url: /fa/aspose.slides.charts/chartdatacell/set_formula/
---
## ChartDataCell::set_Formula(System::String) متد


فرمول را به سبک A1 تنظیم می‌کند.

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Formula(System::String value) override
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