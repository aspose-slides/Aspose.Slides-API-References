---
title: get_Overlap()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد مقدار تداخل الأعمدة والشرائط في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%).
type: docs
weight: 183
url: /ar/aspose.slides.charts/ichartseriesgroup/get_overlap/
---
## IChartSeriesGroup::get_Overlap() طريقة

يحدد مقدار تداخل الأعمدة والشرائط في المخططات ثنائية الأبعاد، كنسبة مئوية (من -100% إلى 100%).

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeriesGroup::get_Overlap()=0
```

## ملاحظات

* -100%: الحد الأقصى للمسافات (الأشرطة مفصولة تمامًا).
* 0%: تُوضع الأشرطة جنبًا إلى جنب دون تداخل أو مسافة.
* 100%: الحد الأقصى للتداخل (الأشرطة تتداخل تمامًا مع بعضها). هذه الخاصية للقراءة والكتابة **int8_t**.

يوضح المثال التالي كيفية تعيين التداخل لمجموعة سلسلة المخطط وعرض المخطط الناتج على نموذج:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // تعيين التداخل إلى 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## انظر أيضًا

* فئة [IChartSeriesGroup](../)
* نطاق [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)