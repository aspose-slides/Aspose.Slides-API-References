---
title: get_Overlap()
second_title: Aspose.Slides for C++ API Referansı
description: 2B grafiklerde çubukların ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir ( -100% ile 100% arasında ).
type: docs
weight: 183
url: /tr/aspose.slides.charts/ichartseriesgroup/get_overlap/
---
## IChartSeriesGroup::get_Overlap() metod

2B grafiklerde çubukların ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir ( -100% ile 100% arasında).

```cpp
virtual int8_t Aspose::Slides::Charts::IChartSeriesGroup::get_Overlap()=0
```

## Açıklamalar

* -100%: Azami boşluk (çubuklar tamamen ayrılmıştır).
* 0%: Çubuklar yan yana, üst üste binme veya boşluk olmadan yerleştirilir.
* 100%: Azami üst üste binme (çubuklar tamamen birbirinin üzerine biner). Bu özellik okuma/yazma **int8_t**.

Aşağıdaki örnek, bir grafik serisi grubu için üst üste binmeyi ayarlamayı ve oluşan grafiği bir formda render etmeyi gösterir:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Üst üste binmeyi %55 olarak ayarla

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## Ayrıca Bakınız

* Sınıf [IChartSeriesGroup](../)
* Ad alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)