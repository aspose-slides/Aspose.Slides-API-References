---
title: set_Value()
second_title: Aspose.Slides برای مرجع API C++
description: "مقدار یک سلول را تنظیم می‌کند. System::Object را بنویسید."
type: docs
weight: 40
url: /fa/aspose.slides.charts/ichartdatacell/set_value/
---
## IChartDataCell::set_Value(System::SharedPtr\<System::Object\>) متد


مقدار یک سلول را تنظیم می‌کند. [System::Object](../../../system/object/) را بنویسید.

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Value(System::SharedPtr<System::Object> value)=0
```

## توضیحات



```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```




## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [IChartDataCell](../)
* فضای نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)