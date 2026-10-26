---
title: get_Categories()
second_title: مرجع API Aspose.Slides للغة C++
description: "يجلب الفئات الأولية (أو كل من الفئات الأولية والثانوية إذا تم تعيين ChartData::set_UseSecondaryCategories إلى false). للقراءة فقط IChartCategoryCollection."
type: docs
weight: 40
url: /ar/aspose.slides.charts/chartdata/get_categories/
---
## ChartData::get_Categories() طريقة

يجلب الفئات الأولية (أو كل من الفئات الأولية والثانوية إذا كان [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) مضبوطًا على false). للقراءة فقط [IChartCategoryCollection](../../ichartcategorycollection/).

```cpp
System::SharedPtr<IChartCategoryCollection> Aspose::Slides::Charts::ChartData::get_Categories() override
```

## ملاحظات

إذا تم ضبط [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) على false فإن [ChartData::get_SecondaryCategories](../get_secondarycategories/) تعيد null والبيانات في [ChartData::get_Categories](./) تُستخدم لكل من السلاسل الأولية والثانوية. إذا تم ضبط [ChartData::set_UseSecondaryCategories](../set_usesecondarycategories/) على true فإن البيانات في [ChartData::get_SecondaryCategories](../get_secondarycategories/) تُستخدم للسلاسل الثانوية والبيانات في [ChartData::get_Categories](./) تُستخدم للسلاسل الأولية.

مثال. ما الفئات المرتبطة بالسلاسل - [ChartData::get_Categories](./) أو [ChartData::get_SecondaryCategories](../get_secondarycategories/)؟

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

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IChartCategoryCollection](../../ichartcategorycollection/)
* فئة [ChartData](../)
* نطاق [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)