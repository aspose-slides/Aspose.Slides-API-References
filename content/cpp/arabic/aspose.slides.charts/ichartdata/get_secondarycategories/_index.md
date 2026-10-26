---
title: get_SecondaryCategories()
second_title: Aspose.Slides لـ C++ مرجع API
description: "يحصل على الفئات الثانوية إذا كان IChartData::get_UseSecondaryCategories صحيحًا. قراءة فقط IChartCategoryCollection."
type: docs
weight: 79
url: /ar/aspose.slides.charts/ichartdata/get_secondarycategories/
---
## IChartData::get_SecondaryCategories() طريقة

يحصل على الفئات الثانوية إذا كان [IChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) صحيحًا. قراءة فقط [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_SecondaryCategories()=0
```

## ملاحظات

إذا تم تعيين [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) إلى false فإن [IChartData::get_SecondaryCategories](./) يعيد null وتُستخدم البيانات في [IChartData::get_Categories](../get_categories/) لكل من السلاسل الأساسية والثانوية. إذا تم تعيين [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) إلى true فإن البيانات في [IChartData::get_SecondaryCategories](./) تُستخدم للسلسلة الثانوية والبيانات في [IChartData::get_Categories](../get_categories/) تُستخدم للسلسلة الأساسية.

مثال. ما هي الفئات المرتبطة بالسلسلة - ChartData.Categories أو ChartData.SecondaryCategories؟
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // الفئات المرتبطة هي series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // الفئات المرتبطة هي series->get_Chart()->get_ChartData()->get_Categories()
}
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IChartCategoryCollection](../../ichartcategorycollection/)
* فئة [IChartData](../)
* نطاق الاسم [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)