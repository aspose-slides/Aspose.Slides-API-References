---
title: set_Overlap()
second_title: Aspose.Slides için C++ API Referansı
description: 2-D grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-100% ile 100% arasında).
type: docs
weight: 170
url: /tr/aspose.slides.charts/chartseriesgroup/set_overlap/
---
## ChartSeriesGroup::set_Overlap(int8_t) metodu

2B grafiklerde çubuk ve sütunların ne kadar üst üste geleceğini yüzde olarak belirtir (-100% ile 100% arasında).

```cpp
void Aspose::Slides::Charts::ChartSeriesGroup::set_Overlap(int8_t value) override
```

## Açıklamalar

* -100%: Azami boşluk (çubuklar tamamen ayrılmıştır).
* 0%: Çubuklar üst üste gelmeden yan yana yer alır.
* 100%: Azami üst üste gelme (çubuklar birbirinin tamamen üstüne biner). Bu özellik okuma/yazma **int8_t**.

Aşağıdaki örnek, bir grafik serisi grubunun üst üste gelme miktarının nasıl ayarlanacağını ve oluşan grafiğin bir forma nasıl çizileceğini gösterir:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Üst üste gelmeyi %55 olarak ayarla

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```

## Ayrıca Bakınız

* Sınıf [ChartSeriesGroup](../)
* Ad alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)