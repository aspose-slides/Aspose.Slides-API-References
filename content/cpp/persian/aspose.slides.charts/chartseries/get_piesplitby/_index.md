---
title: get_PieSplitBy()
second_title: Aspose.Slides برای مرجع API C++
description: مشخص می‌کند چگونه نقاط داده را که در پای دوم یا نوار دوم در نمودار pie-of-pie یا bar-of-pie هستند، تعیین کنیم. این ویژگی نه فقط متعلق به این سری است بلکه به تمام سری‌های گروه سری والد تعلق دارد – این یک تصویر از ویژگی مناسب گروه است. بنابراین این ویژگی فقط-خواندنی است. برای دسترسی به گروه سری والد از ویژگی ParentSeriesGroup استفاده کنید. برای تغییر مقدار از ویژگی خواندنی/قابل نوشتن get_ParentSeriesGroup()->get(set)_PieSplitBy() استفاده کنید. فقط-خواندنی PieSplitType.
type: docs
weight: 755
url: /fa/aspose.slides.charts/chartseries/get_piesplitby/
---
## ChartSeries::get_PieSplitBy() متد

مشخص می‌کند چگونه نقاط داده را که در پای دوم یا نوار دوم در نمودار pie-of-pie یا bar-of-pie قرار دارند، تعیین کنیم. این ویژگی نه تنها متعلق به این سری است بلکه به تمام سری‌های گروه سری والد (ParentSeriesGroup) تعلق دارد – این یک تصویر از ویژگی مربوط به گروه است. بنابراین این ویژگی فقط-خواندنی است. از ویژگی ParentSeriesGroup برای دسترسی به گروه سری والد استفاده کنید. برای تغییر مقدار، از ویژگی خواندنی/قابل نوشتن [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() استفاده کنید. فقط-خواندنی [PieSplitType](../../piesplittype/).

```cpp
PieSplitType Aspose::Slides::Charts::ChartSeries::get_PieSplitBy() override
```

## توضیحات

1) این تصویر از ویژگی [get_ParentSeriesGroup()](../get_parentseriesgroup/)->get(set)_PieSplitBy() است. 2) اگر مقدار ویژگی [PieSplitType::Custom](../../piesplittype/) باشد، می‌توانید اطلاعات تقسیم سفارشی را با ویژگی [get_ParentSeriesGroup()](../get_parentseriesgroup/)->[get_PieSplitCustomPoints()](../get_piesplitcustompoints/) تعریف کنید.

## مراجع

* Enum [PieSplitType](../../piesplittype/)
* کلاس [ChartSeries](../)
* فضای‌نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)