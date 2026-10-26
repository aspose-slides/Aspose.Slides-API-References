---
title: set_Overlap()
second_title: مرجع Aspose.Slides للـ C++ API
description: يحدد مقدار تداخل الأشرطة والأعمدة في الرسوم البيانية ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%).
type: docs
weight: 196
url: /ar/aspose.slides.charts/ichartseriesgroup/set_overlap/
---
## IChartSeriesGroup::set_Overlap(int8_t) طريقة

يحدد مقدار تداخل الأشرطة والأعمدة على الرسوم البيانية ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%).

```cpp
virtual void Aspose::Slides::Charts::IChartSeriesGroup::set_Overlap(int8_t value)=0
```

## ملاحظات

* -100%: أقصى مسافة (الأشرطة مفصولة تمامًا).
* 0%: تُوضع الأشرطة جنبًا إلى جنب دون تداخل أو فراغ.
* 100%: أقصى تداخل (الأشرطة تتداخل تمامًا مع بعضها). هذه الخاصية للقراءة والكتابة **int8_t**.

المثال التالي يوضح كيفية ضبط التداخل لمجموعة سلسلة المخطط وعرض المخطط الناتج على نموذج:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // ضبط التداخل إلى 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## انظر أيضًا

* الفئة [IChartSeriesGroup](../)
* النطاق [Aspose::Slides::Charts](../../)
* المكتبة [Aspose.Slides](../../../)