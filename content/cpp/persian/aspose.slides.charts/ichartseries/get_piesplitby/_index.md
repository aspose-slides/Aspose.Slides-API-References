---
title: get_PieSplitBy()
second_title: Aspose.Slides برای C++ مرجع API
description: مشخص می‌کند که چگونه تعیین شود کدام نقاط داده در دایره یا نوار دوم در نمودار pie-of-pie یا bar-of-pie قرار دارند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک نمایش از ویژگی مناسب گروه است. بنابراین این ویژگی فقط خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی get_ParentSeriesGroup()->get(set)_PieSplitBy() که قابل خواندن/نوشتن است استفاده کنید. فقط خواندنی PieSplitType.
type: docs
weight: 729
url: /fa/aspose.slides.charts/ichartseries/get_piesplitby/
---
## IChartSeries::get_PieSplitBy() متد

مشخص می‌کند که چگونه تعیین شود کدام نقاط داده در دایره یا نوار دوم در نمودار pie-of-pie یا bar-of-pie قرار دارند. این ویژگی نه تنها برای این سری بلکه برای تمام سری‌های گروه سری والد است - این یک نمایش از ویژگی مناسب گروه است. بنابراین این ویژگی فقط خواندنی است. از ویژگی ParentSeriesGroup برای دسترسی به گروه سری والد استفاده کنید. از [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() ویژگی قابل خواندن/نوشتن برای تغییر مقدار استفاده کنید. فقط خواندنی [PieSplitType](../../piesplittype/).

```cpp
virtual PieSplitType Aspose::Slides::Charts::IChartSeries::get_PieSplitBy()=0
```

## توضیحات

1) این یک نمایش از ویژگی [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() است. 2) اگر مقدار ویژگی [PieSplitType::Custom](../../piesplittype/) باشد می‌توانید اطلاعات تقسیم سفارشی را با ویژگی [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/) تعریف کنید.

## موارد مرتبط

* Enum [PieSplitType](../../piesplittype/)
* کلاس [IChartSeries](../)
* فضای‌نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)