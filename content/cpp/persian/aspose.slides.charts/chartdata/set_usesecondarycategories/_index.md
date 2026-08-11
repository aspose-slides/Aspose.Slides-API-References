---
title: set_UseSecondaryCategories()
second_title: Aspose.Slides برای مرجع API C++
description: "اگر مقدار به false تنظیم شود، ChartData::get_SecondaryCategories مقدار null را برمی‌گرداند و داده‌های موجود در ChartData::get_Categories هم برای سری‌های اولیه و هم ثانوی استفاده می‌شود. اگر مقدار به true تنظیم شود، داده‌های موجود در ChartData::get_SecondaryCategories برای سری‌های ثانوی استفاده می‌شوند و داده‌های موجود در ChartData::get_Categories برای سری‌های اولیه استفاده می‌شوند. مقدار باید از نوع bool باشد."
type: docs
weight: 66
url: /fa/aspose.slides.charts/chartdata/set_usesecondarycategories/
---
## ChartData::set_UseSecondaryCategories(bool) متد

اگر مقدار به false تنظیم شود، [ChartData::get_SecondaryCategories](../get_secondarycategories/) مقدار null را برمی‌گرداند و داده‌های موجود در [ChartData::get_Categories](../get_categories/) برای هر دو سری اصلی و ثانوی استفاده می‌شود. اگر مقدار به true تنظیم شود، داده‌های موجود در [ChartData::get_SecondaryCategories](../get_secondarycategories/) برای سری ثانوی استفاده می‌شوند و داده‌های موجود در [ChartData::get_Categories](../get_categories/) برای سری اصلی استفاده می‌شوند. نوشتن **bool**.

```cpp
void Aspose::Slides::Charts::ChartData::set_UseSecondaryCategories(bool value) override
```

## ملاحظات

مثال. چه دسته‌بندی‌هایی به سری مربوط هستند - [ChartData::get_Categories](../get_categories/) یا [ChartData::get_SecondaryCategories](../get_secondarycategories/)؟

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

## همچنین ببینید

* کلاس [ChartData](../)
* فضای نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)