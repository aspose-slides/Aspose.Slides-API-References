---
title: get_SecondaryCategories()
second_title: مرجع API Aspose.Slides برای C++
description: "دسته‌بندی‌های ثانویه را در صورتی که IChartData::get_UseSecondaryCategories صحیح باشد، دریافت می‌کند. فقط‌خواندنی IChartCategoryCollection."
type: docs
weight: 79
url: /fa/aspose.slides.charts/ichartdata/get_secondarycategories/
---
## IChartData::get_SecondaryCategories() متد

دریافت می‌کند دسته‌بندی‌های ثانویه را در صورتی که [IChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) صحیح باشد. فقط‌خواندنی [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_SecondaryCategories()=0
```

## توضیحات

اگر [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) برابر false باشد، [IChartData::get_SecondaryCategories](./) مقدار null برمی‌گرداند و داده‌های موجود در [IChartData::get_Categories](../get_categories/) هم برای سلسله اولیه و هم برای سلسله ثانویه استفاده می‌شود. اگر [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) برابر true باشد، داده‌های موجود در [IChartData::get_SecondaryCategories](./) برای سلسله ثانویه استفاده می‌شود و داده‌های موجود در [IChartData::get_Categories](../get_categories/) برای سلسله اولیه استفاده می‌شود.

مثال. کدام دسته‌بندی‌ها به سلسله مرتبط هستند - ChartData.Categories یا ChartData.SecondaryCategories؟

```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // دسته‌‏های مرتبط عبارتند از series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // دسته‌‏های مرتبط عبارتند از series->get_Chart()->get_ChartData()->get_Categories()
}
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IChartCategoryCollection](../../ichartcategorycollection/)
* کلاس [IChartData](../)
* فضای‌نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)