---
title: set_Value()
second_title: مرجع API Aspose.Slides برای C++
description: "مقدار یک سلول را تنظیم می‌کند. System::Object را بنویسید."
type: docs
weight: 40
url: /fa/aspose.slides.charts/chartdatacell/set_value/
---
## ChartDataCell::set_Value(System::SharedPtr\<System::Object\>) متد

مقدار یک سلول را تنظیم می‌کند. [System::Object](../../../system/object/) را بنویسید.

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Value(System::SharedPtr<System::Object> value) override
```

## یادداشت‌ها

```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [ChartDataCell](../)
* فضای نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)