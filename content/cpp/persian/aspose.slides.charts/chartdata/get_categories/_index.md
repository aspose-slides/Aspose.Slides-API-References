---
title: get_Categories()
second_title: Aspose.Slides برای C++ مرجع API
description: "دسته‌بندی‌های اصلی را دریافت می‌کند (یا هر دو دسته‌بندی اصلی و فرعی اگر ChartData::set_UseSecondaryCategories برابر false باشد). فقط‌خواندنی IChartCategoryCollection."
type: docs
weight: 40
url: /fa/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() متد

دسته‌بندی‌های اصلی را دریافت می‌کند (یا هر دو دسته‌بندی اصلی و فرعی اگر [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) برابر false تنظیم شده باشد). فقط‌خواندنی [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## توضیحات

اگر [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) برابر false تنظیم شود، سپس [ChartData::get_SecondaryCategories](../get_secondarycategories/) مقدار null برمی‌گرداند و داده‌های موجود در [ChartData::get_Categories](./) برای هر دو سری اصلی و فرعی استفاده می‌شود. اگر [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) برابر true تنظیم شود، داده‌های موجود در [ChartData::get_SecondaryCategories](../get_secondarycategories/) برای سری‌های فرعی استفاده می‌شود و داده‌های موجود در [ChartData::get_Categories](./) برای سری‌های اصلی استفاده می‌شود.

مثال. کدام دسته‌بندی‌ها با سری مرتبط هستند - [ChartData::get_Categories](./) یا [ChartData::get_SecondaryCategories](../get_secondarycategories/)؟

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
* کلاس [ChartData](../)
* فضای‌نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)