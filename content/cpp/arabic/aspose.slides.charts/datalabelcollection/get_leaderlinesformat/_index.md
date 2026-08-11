---
title: get_LeaderLinesFormat()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل تنسيق خطوط القادة لتسميات البيانات. قراءة فقط IChartLinesFormat.
type: docs
weight: 66
url: /ar/aspose.slides.charts/datalabelcollection/get_leaderlinesformat/
---
## DataLabelCollection::get_LeaderLinesFormat() طريقة

يمثل تنسيق خطوط القادة لتسميات البيانات. قراءة فقط [IChartLinesFormat](../../ichartlinesformat/).

```cpp
System::SharedPtr<IChartLinesFormat> Aspose::Slides::Charts::DataLabelCollection::get_LeaderLinesFormat() override
```

## ملاحظات

مثال: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IChart> chart = System::ExplicitCast<IChart>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
System::SharedPtr<IDataLabelCollection> labels = series->idx_get(0)->get_Labels();
System::SharedPtr<ILineFillFormat> fillFormat = labels->get_LeaderLinesFormat()->get_Line()->get_FillFormat();

fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::FromArgb(255, 255, 0, 0));
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IChartLinesFormat](../../ichartlinesformat/)
* فئة [DataLabelCollection](../)
* مساحة الاسم [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)