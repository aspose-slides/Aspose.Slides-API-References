---
title: get_LeaderLinesFormat()
second_title: Aspose.Slides C++ için API Referansı
description: Veri etiketlerinin lider çizgi biçimini temsil eder. Yalnızca okuma IChartLinesFormat.
type: docs
weight: 14
url: /tr/aspose.slides.charts/idatalabelcollection/get_leaderlinesformat/
---
## IDataLabelCollection::get_LeaderLinesFormat() metod

Veri etiketlerinin lider çizgi biçimini temsil eder. Yalnızca okuma [IChartLinesFormat](../../ichartlinesformat/).

```cpp
virtual System::SharedPtr<IChartLinesFormat> Aspose::Slides::Charts::IDataLabelCollection::get_LeaderLinesFormat()=0
```

## Açıklamalar

Örnek:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IChart> chart = System::ExplicitCast<IChart>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
System::SharedPtr<IDataLabelCollection> labels = series->idx_get(0)->get_Labels();
System::SharedPtr<ILineFillFormat> fillFormat = labels->get_LeaderLinesFormat()->get_Line()->get_FillFormat();

fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::FromArgb(255, 255, 0, 0));
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChartLinesFormat](../../ichartlinesformat/)
* Sınıf [IDataLabelCollection](../)
* İsim alanı [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)