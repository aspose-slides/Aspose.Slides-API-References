---
title: CalculateFormulas()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحسب جميع الصيغ في دفتر العمل ويحدّث قيم الخلايا المقابلة.
type: docs
weight: 53
url: /ar/aspose.slides.charts/chartdataworkbook/calculateformulas/
---
## ChartDataWorkbook::CalculateFormulas() طريقة

يقوم بحساب جميع الصيغ في دفتر العمل وتحديث قيم الخلايا المقابلة.

```cpp
void Aspose::Slides::Charts::ChartDataWorkbook::CalculateFormulas() override
```

## ملاحظات



يوضح المثال كيفية تعيين صيغة للخلية وكيفية حساب قيمة. يتم تعيين قيمة الخلية \"B4\" إلى 5. 
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 100.0f, 100.0f, 300.0f, 400.0f);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();
wb->GetCell(0, u"B2", ObjectExt::Box<int32_t>(2));
wb->GetCell(0, u"B3", ObjectExt::Box<int32_t>(3));
wb->GetCell(0, u"B4")->set_Formula(u"B2+B3");
wb->CalculateFormulas();
//...
```

## انظر أيضا

* فئة [ChartDataWorkbook](../)
* مساحة الاسم [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)