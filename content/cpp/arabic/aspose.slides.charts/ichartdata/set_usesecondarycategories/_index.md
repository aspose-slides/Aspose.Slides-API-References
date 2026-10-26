---
title: set_UseSecondaryCategories()
second_title: مرجع API Aspose.Slides للغة C++
description: "إذا تم الضبط على false فتُعيد IChartData::get_SecondaryCategories القيمة null وتُستخدم البيانات في IChartData::get_Categories لكل من السلاسل الأولية والثانوية. إذا تم الضبط على true فتُستخدم البيانات في IChartData::get_SecondaryCategories للسلاسل الثانوية وتُستخدم البيانات في IChartData::get_Categories للسلاسل الأولية. اكتب bool."
type: docs
weight: 66
url: /ar/aspose.slides.charts/ichartdata/set_usesecondarycategories/
---
## IChartData::set_UseSecondaryCategories(bool) طريقة

إذا تم الضبط على false فإن [IChartData::get_SecondaryCategories](../get_secondarycategories/) تعيد null والبيانات في [IChartData::get_Categories](../get_categories/) تُستخدم لكل من السلاسل الأولية والثانوية. إذا تم الضبط على true فإن البيانات في [IChartData::get_SecondaryCategories](../get_secondarycategories/) تُستخدم للسلاسل الثانوية والبيانات في [IChartData::get_Categories](../get_categories/) تُستخدم للسلاسل الأولية. اكتب **bool**.

```cpp
virtual void Aspose::Slides::Charts::IChartData::set_UseSecondaryCategories(bool value)=0
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

* فئة [IChartData](../)
* مساحة الاسم [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)