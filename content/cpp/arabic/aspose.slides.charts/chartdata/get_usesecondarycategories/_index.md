---
title: get_UseSecondaryCategories()
second_title: Aspose.Slides لـ C++ مرجع API
description: "إذا تم تعيينه إلى false فستُرجع ChartData::get_SecondaryCategories null وتُستخدم البيانات في ChartData::get_Categories لكلا السلسلتين الأساسية والثانوية. إذا تم تعيينه إلى true فستُستخدم البيانات في ChartData::get_SecondaryCategories للسلسلة الثانوية والبيانات في ChartData::get_Categories للسلسلة الأساسية. اقرأ bool."
type: docs
weight: 53
url: /ar/aspose.slides.charts/chartdata/get_usesecondarycategories/
---
## ChartData::get_UseSecondaryCategories() طريقة


إذا تم تعيينه إلى false فستُرجع [ChartData::get_SecondaryCategories](../get_secondarycategories/) null وتُستخدم البيانات في [ChartData::get_Categories](../get_categories/) لكلاً من السلسلة الأساسية والثانوية. إذا تم تعيينه إلى true فستُستخدم البيانات في [ChartData::get_SecondaryCategories](../get_secondarycategories/) للسلسلة الثانوية والبيانات في [ChartData::get_Categories](../get_categories/) للسلسلة الأساسية. اقرأ **bool**.

```cpp
bool Aspose::Slides::Charts::ChartData::get_UseSecondaryCategories() override
```

## ملاحظات


مثال. ما الفئات المرتبطة بالسلسلة - [ChartData::get_Categories](../get_categories/) أو [ChartData::get_SecondaryCategories](../get_secondarycategories/)؟ 
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

* فئة [ChartData](../)
* مساحة الاسم [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)