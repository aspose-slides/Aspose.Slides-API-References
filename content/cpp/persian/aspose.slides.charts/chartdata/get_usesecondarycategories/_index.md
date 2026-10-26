---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides برای مرجع API C++
description: "اگر false باشد، ChartData::get_SecondaryCategories مقدار null برمی‌گرداند و داده‌های ChartData::get_Categories هم برای سری اصلی و هم برای سری ثانویه استفاده می‌شوند. اگر true باشد، داده‌های ChartData::get_SecondaryCategories برای سری ثانویه استفاده می‌شوند و داده‌های ChartData::get_Categories برای سری اصلی استفاده می‌شوند. خواندن bool."
type: docs
weight: 53
url: /fa/aspose.slides.charts/chartdata/get_usesecondarycategories/
---
## ChartData::get_UseSecondaryCategories() متد

If set to false then [ChartData::get_SecondaryCategories](../get_secondarycategories/) returns null and data in [ChartData::get_Categories](../get_categories/) is used both for primary and secondary series. If set to true then data in [ChartData::get_SecondaryCategories](../get_secondarycategories/) is used for secondary series and data in [ChartData::get_Categories](../get_categories/) is used for primary series. Read **bool**.

```cpp
bool Aspose::Slides::Charts::ChartData::get_UseSecondaryCategories() override
```

## توضیحات

مثال. چه دسته‌بندی‌هایی به سری - [ChartData::get_Categories](../get_categories/) یا [ChartData::get_SecondaryCategories](../get_secondarycategories/) مرتبط هستند؟

```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // دسته‌بندی‌های مرتبط series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // دسته‌بندی‌های مرتبط series->get_Chart()->get_ChartData()->get_Categories()
}
```

## همچنین ببینید

* کلاس [ChartData](../)
* فضای نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)