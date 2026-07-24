---
title: get_Overlap()
second_title: Aspose.Slides for C++ API Referansı
description: 2-D grafiklerde çubukların ve sütunların ne kadar üst üste bineceğini yüzde olarak belirler (-100% ile 100% arasında).
type: docs
weight: 157
url: /tr/aspose.slides.charts/chartseriesgroup/get_overlap/
---
## ChartSeriesGroup::get_Overlap() yöntemi


2-D grafiklerde çubukların ve sütunların ne kadar üst üste bineceğini yüzde olarak belirler (-100% ile 100% arasında).

```cpp
int8_t Aspose::Slides::Charts::ChartSeriesGroup::get_Overlap() override
```

## Açıklamalar


* -100%: Maksimum boşluk (çubuklar tamamen ayrılmıştır).
* 0%: Çubuklar üst üste binmeden ve boşluk olmadan yan yana yerleştirilir.
* 100%: Maksimum üst üste binme (çubuklar birbirinin tamamen üzerine gelir). Bu özellik okuma/yazma **int8_t**.



Aşağıdaki örnek, bir grafik serisi grubu için üst üste binmeyi nasıl ayarlayacağınızı ve oluşan grafiği bir formda nasıl render edeceğinizi gösterir: 
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

* Sınıf [ChartSeriesGroup](../)
* AdAlanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)