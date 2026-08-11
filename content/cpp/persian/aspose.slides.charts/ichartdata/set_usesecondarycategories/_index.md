---
title: set_UseSecondaryCategories()
second_title: مرجع API Aspose.Slides برای C++
description: "اگر به مقدار false تنظیم شود، IChartData::get_SecondaryCategories مقدار null را برمی‌گرداند و داده‌های موجود در IChartData::get_Categories هم برای سری‌های اصلی و هم ثانویه استفاده می‌شوند. اگر به مقدار true تنظیم شود، داده‌های موجود در IChartData::get_SecondaryCategories برای سری‌های ثانویه استفاده می‌شوند و داده‌های موجود در IChartData::get_Categories برای سری‌های اصلی استفاده می‌شوند. نوشتن bool."
type: docs
weight: 66
url: /fa/aspose.slides.charts/ichartdata/set_usesecondarycategories/
---
## IChartData::set_UseSecondaryCategories(bool) متد


اگر به مقدار false تنظیم شود، [IChartData::get_SecondaryCategories](../get_secondarycategories/) مقدار null را برمی‌گرداند و داده‌های موجود در [IChartData::get_Categories](../get_categories/) برای سری‌های اصلی و ثانویه استفاده می‌شود. اگر به مقدار true تنظیم شود، داده‌های موجود در [IChartData::get_SecondaryCategories](../get_secondarycategories/) برای سری‌های ثانویه استفاده می‌شود و داده‌های موجود در [IChartData::get_Categories](../get_categories/) برای سری‌های اصلی استفاده می‌شود. نوشتن **bool**.

```cpp
virtual void Aspose::Slides::Charts::IChartData::set_UseSecondaryCategories(bool value)=0
```

## توضیحات


مثال. کدام دسته‌بندی‌ها به سری‌ها مرتبط هستند - ChartData.Categories یا ChartData.SecondaryCategories؟
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // دسته‌بندی‌های مرتبط عبارتند از series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // دسته‌بندی‌های مرتبط عبارتند از series->get_Chart()->get_ChartData()->get_Categories()
}
```

## موارد مرتبط

* کلاس [IChartData](../)
* فضای نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)