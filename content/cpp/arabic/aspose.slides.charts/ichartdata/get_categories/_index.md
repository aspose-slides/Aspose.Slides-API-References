---
title: get_Categories()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يحصل على الفئات الأساسية (أو كل من الفئات الأساسية والثانوية إذا تم تعيين IChartData::set_UseSecondaryCategories إلى false). للقراءة فقط IChartCategoryCollection."
type: docs
weight: 40
url: /ar/aspose.slides.charts/ichartdata/get_categories/
---
## IChartData::get_Categories() طريقة

يحصل على الفئات الأساسية (أو كل من الفئات الأساسية والثانوية إذا تم تعيين [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) إلى false). للقراءة فقط [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
virtual System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::IChartData::get_Categories()=0
```

## ملاحظات

إذا تم تعيين [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) إلى false فإن [IChartData::get_SecondaryCategories](../get_secondarycategories/) تعيد null والبيانات في [IChartData::get_Categories](./) تُستخدم لكل من السلاسل الأساسية والثانوية. إذا تم تعيين [IChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) إلى true فإن البيانات في [IChartData::get_SecondaryCategories](../get_secondarycategories/) تُستخدم للسلاسل الثانوية والبيانات في [IChartData::get_Categories](./) تُستخدم للسلاسل الأساسية.

مثال. ما هي الفئات المرتبطة بالسلاسل - ChartData.Categories أو ChartData.SecondaryCategories؟

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

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [IChartCategoryCollection](../../ichartcategorycollection/)
* الفئة [IChartData](../)
* المجال [Aspose::Slides::Charts](../../)
* المكتبة [Aspose.Slides](../../../)