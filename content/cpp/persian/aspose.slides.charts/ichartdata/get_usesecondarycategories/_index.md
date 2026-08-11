---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides برای مرجع API C++
description: "اگر به false تنظیم شود، IChartData::get_SecondaryCategories مقدار null را برمی‌گرداند و داده‌های IChartData::get_Categories هم برای سری‌های اولیه و هم ثانویه استفاده می‌شوند. اگر به true تنظیم شود، داده‌های IChartData::get_SecondaryCategories برای سری‌های ثانویه و داده‌های IChartData::get_Categories برای سری‌های اولیه استفاده می‌شوند. خواندن bool."
type: docs
weight: 53
url: /fa/aspose.slides.charts/ichartdata/get_usesecondarycategories/
---
## IChartData::get_UseSecondaryCategories() متد

اگر به false تنظیم شود، [IChartData::get_SecondaryCategories](../get_secondarycategories/) مقدار null را برمی‌گرداند و داده‌های [IChartData::get_Categories](../get_categories/) برای هر دو سری اولیه و ثانویه استفاده می‌شوند. اگر به true تنظیم شود، داده‌های [IChartData::get_SecondaryCategories](../get_secondarycategories/) برای سری ثانویه و داده‌های [IChartData::get_Categories](../get_categories/) برای سری اولیه استفاده می‌شوند. خواندن **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IChartData::get_UseSecondaryCategories()=0
```

## یادداشت‌ها

مثال. چه دسته‌هایی به سری‌ها مرتبط هستند - ChartData.Categories یا ChartData.SecondaryCategories؟
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // دسته‌های مرتبط عبارتند از series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // دسته‌های مرتبط عبارتند از series->get_Chart()->get_ChartData()->get_Categories()
}
```

## موارد مرتبط

* کلاس [IChartData](../)
* فضای‌نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)