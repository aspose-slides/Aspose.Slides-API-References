---
title: get_SecondaryCategories()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يحصل على الفئات الثانوية إذا كان ChartData::get_UseSecondaryCategories صحيحًا. للقراءة فقط IChartCategoryCollection."
type: docs
weight: 79
url: /ar/aspose.slides.charts/chartdata/get_secondarycategories/
---
## ChartData::get_SecondaryCategories() طريقة

يحصل على الفئات الثانوية إذا كان [ChartData::get_UseSecondaryCategories](../get_usesecondarycategories/) صحيحًا. للقراءة فقط [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_SecondaryCategories() override
```

## ملاحظات

إذا تم تعيين [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) إلى false فإن [ChartData::get_SecondaryCategories](./) تُعيد null وتُستخدم البيانات في [ChartData::get_Categories](../get_categories/) لكل من السلاسل الأولية والثانوية. إذا تم تعيين [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) إلى true فإن البيانات في [ChartData::get_SecondaryCategories](./) تُستخدم للسلسلة الثانوية والبيانات في [ChartData::get_Categories](../get_categories/) تُستخدم للسلسلة الأولية.

مثال. ما هي الفئات المرتبطة بالسلسلة - [ChartData::get_Categories](../get_categories/) أو [ChartData::get_SecondaryCategories](./)؟

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
* فئة [ChartData](../)
* نطاق [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)