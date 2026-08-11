---
title: set_UseSecondaryCategories()
second_title: مرجع API Aspose.Slides للغة C++
description: "إذا تم ضبطه على false فإن ChartData::get_SecondaryCategories يعيد null وتُستخدم البيانات في ChartData::get_Categories لكل من السلاسل الأساسية والثانوية. إذا تم ضبطه على true فإن البيانات في ChartData::get_SecondaryCategories تُستخدم للسلاسل الثانوية والبيانات في ChartData::get_Categories تُستخدم للسلاسل الأساسية. اكتب bool."
type: docs
weight: 66
url: /ar/aspose.slides.charts/chartdata/set_usesecondarycategories/
---
## ChartData::set_UseSecondaryCategories(bool) طريقة

إذا تم ضبطه على false فإن [ChartData::get_SecondaryCategories](../get_secondarycategories/) يعيد null وتُستخدم البيانات في [ChartData::get_Categories](../get_categories/) لكل من السلاسل الأساسية والثانوية. إذا تم ضبطه على true فإن البيانات في [ChartData::get_SecondaryCategories](../get_secondarycategories/) تُستخدم للسلاسل الثانوية والبيانات في [ChartData::get_Categories](../get_categories/) تُستخدم للسلاسل الأساسية. اكتب **bool**.

```cpp
void Aspose::Slides::Charts::ChartData::set_UseSecondaryCategories(bool value) override
```

## ملاحظات

مثال. ما الفئات المرتبطة بالسلسلة - [ChartData::get_Categories](../get_categories/) أو [ChartData::get_SecondaryCategories](../get_secondarycategories/)؟

```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // الفئات ذات الصلة هي series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // الفئات ذات الصلة هي series->get_Chart()->get_ChartData()->get_Categories()
}
```

## انظر أيضًا

* فئة [ChartData](../)
* نطاق [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)