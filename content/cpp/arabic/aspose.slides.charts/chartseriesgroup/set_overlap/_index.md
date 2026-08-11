---
title: set_Overlap()
second_title: مرجع API Aspose.Slides للـ C++
description: يحدد مقدار التداخل بين الأشرطة والأعمدة في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%).
type: docs
weight: 170
url: /ar/aspose.slides.charts/chartseriesgroup/set_overlap/
---
## ChartSeriesGroup::set_Overlap(int8_t) طريقة

Specifies how much bars and columns shall overlap on 2-D charts, as a percentage (from -100% to 100%).
```cpp
void Aspose::Slides::Charts::ChartSeriesGroup::set_Overlap(int8_t value) override
```

## ملاحظات

* -100%: أقصى مسافة (الأشرطة منفصلة تمامًا).
* 0%: الأشرطة موضوعة جنبًا إلى جنب دون تداخل أو مسافة.
* 100%: أقصى تداخل (الأشرطة تتداخل تمامًا مع بعضها البعض). هذه الخاصية قابلة للقراءة والكتابة **int8_t**.

المثال التالي يوضح كيفية تعيين التداخل لمجموعة سلسلة مخطط وعرض المخطط الناتج على نموذج:
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

* الفئة [ChartSeriesGroup](../)
* النطاق [Aspose::Slides::Charts](../../)
* المكتبة [Aspose.Slides](../../../)