---
title: get_Categories()
second_title: مرجع API Aspose.Slides برای C++
description: "دسته‌های اصلی را دریافت می‌کند (یا هم دسته‌های اصلی و هم دسته‌های ثانویه اگر IChartData::set_UseSecondaryCategories روی false تنظیم شده باشد). فقط-خواندنی IChartCategoryCollection."
type: docs
weight: 40
url: /fa/aspose.slides.charts/ichartdata/get_categories/
---
## IChartData::get_Categories() متد

دسته‌های اصلی را دریافت می‌کند (یا هم دسته‌های اصلی و هم دسته‌های ثانویه اگر [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) روی false تنظیم شده باشد). فقط-خواندنی [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## توضیحات

اگر [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) روی false تنظیم شود، [IChartData::get_SecondaryCategories](../get_secondarycategories/) مقدار null برمی‌گرداند و داده‌های موجود در [IChartData::get_Categories](./) برای هر دو سری اصلی و ثانویه استفاده می‌شود. اگر [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) روی true تنظیم شود، داده‌های موجود در [IChartData::get_SecondaryCategories](../get_secondarycategories/) برای سری ثانویه و داده‌های موجود در [IChartData::get_Categories](./) برای سری اصلی استفاده می‌شوند.

مثال. چه دسته‌هایی به سری‌ها مرتبط هستند - ChartData.Categories یا ChartData.SecondaryCategories؟
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // related categories are series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // related categories are series->get_Chart()->get_ChartData()->get_Categories()
}
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IChartCategoryCollection](../../ichartcategorycollection/)
* کلاس [IChartData](../)
* فضای‌نام [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)