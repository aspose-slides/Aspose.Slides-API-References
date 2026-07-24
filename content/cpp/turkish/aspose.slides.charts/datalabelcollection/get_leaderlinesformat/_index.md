---
title: get_LeaderLinesFormat()
second_title: Aspose.Slides for C++ API Referansı
description: Veri etiketlerinin lider çizgileri biçimini temsil eder. Salt-okunur IChartLinesFormat.
type: docs
weight: 66
url: /tr/aspose.slides.charts/datalabelcollection/get_leaderlinesformat/
---
## DataLabelCollection::get_LeaderLinesFormat() metodu


Veri etiketlerinin lider çizgileri biçimini temsil eder. Salt-okunur [IChartLinesFormat](../../ichartlinesformat/).

```cpp
System::SharedPtr<IChartLinesFormat> Aspose::Slides::Charts::DataLabelCollection::get_LeaderLinesFormat() override
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

## Bakınız

* Tip tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChartLinesFormat](../../ichartlinesformat/)
* Sınıf [DataLabelCollection](../)
* İsim alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)