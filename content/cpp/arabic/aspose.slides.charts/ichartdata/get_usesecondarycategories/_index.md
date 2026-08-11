---
title: get_UseSecondaryCategories()
second_title: مرجع API Aspose.Slides للـ C++
description: "إذا تم تعيينه إلى false فإن IChartData::get_SecondaryCategories تُرجع null وتُستخدم البيانات في IChartData::get_Categories لكل من السلسلة الأساسية والثانوية. إذا تم تعيينه إلى true فإن البيانات في IChartData::get_SecondaryCategories تُستخدم للسلسلة الثانوية والبيانات في IChartData::get_Categories تُستخدم للسلسلة الأساسية. اقرأ bool."
type: docs
weight: 53
url: /ar/aspose.slides.charts/ichartdata/get_usesecondarycategories/
---
## IChartData::get_UseSecondaryCategories() طريقة


إذا تم تعيينها إلى false فإن [IChartData::get_SecondaryCategories](../get_secondarycategories/) تُرجع null وتُستخدم البيانات في [IChartData::get_Categories](../get_categories/) لكل من السلسلة الأساسية والثانوية. إذا تم تعيينها إلى true فإن البيانات في [IChartData::get_SecondaryCategories](../get_secondarycategories/) تُستخدم للسلسلة الثانوية والبيانات في [IChartData::get_Categories](../get_categories/) تُستخدم للسلسلة الأساسية. اقرأ **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IChartData::get_UseSecondaryCategories()=0
```

## ملاحظات


مثال. ما الفئات المرتبطة بالسلسلة - ChartData.Categories أو ChartData.SecondaryCategories؟ 
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

* الفئة [IChartData](../)
* النطاق [Aspose::Slides::Charts](../../)
* المكتبة [Aspose.Slides](../../../)