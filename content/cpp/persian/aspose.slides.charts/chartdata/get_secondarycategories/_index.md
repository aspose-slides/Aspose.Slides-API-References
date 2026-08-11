---
title: get_SecondaryCategories()
second_title: Aspose.Slides برای C++ مرجع API
description: "دسته‌بندی‌های ثانوی را در صورت صحیح بودن ChartData::get_UseSecondaryCategories دریافت می‌کند. فقط-خواندنی IChartCategoryCollection."
type: docs
weight: 79
url: /fa/aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() متد

دسته‌بندی‌های ثانوی را در صورت صحیح بودن [ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) دریافت می‌کند. فقط خواندنی [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## توضیحات

اگر [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) روی false تنظیم شود، سپس [ChartData::get_SecondaryCategories](./) مقدار null بازمی‌گرداند و داده‌های موجود در [ChartData::get_Categories](../get_categories/) برای سری‌های اصلی و ثانوی استفاده می‌شود. اگر [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) روی true تنظیم شود، داده‌های موجود در [ChartData::get_SecondaryCategories](./) برای سری‌های ثانوی و داده‌های موجود در [ChartData::get_Categories](../get_categories/) برای سری‌های اصلی استفاده می‌شود.

مثال. چه دسته‌بندی‌هایی به سری‌ها مرتبط هستند - [ChartData::get_Categories](../get_categories/) یا [ChartData::get_SecondaryCategories](./)؟
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

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IChartCategoryCollection](../../ichartcategorycollection/)
* کلاس [ChartData](../)
* فضای نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)