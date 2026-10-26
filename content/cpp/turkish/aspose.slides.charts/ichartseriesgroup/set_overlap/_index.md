---
title: set_Overlap()
second_title: Aspose.Slides for C++ API Referansı
description: 2D çizelgelerde çubuk ve sütunların ne kadar örtüşeceğini yüzde olarak belirtir (-100% ile 100% arasında).
type: docs
weight: 196
url: /tr/aspose.slides.charts/ichartseriesgroup/set_overlap/
---
## IChartSeriesGroup::set_Overlap(int8_t) metot


2-D çizelgelerde çubuk ve sütunların ne kadar örtüştüğünü yüzde olarak belirtir (-100% ile 100% arasında).

```cpp
virtual void Aspose::Slides::Charts::IChartSeriesGroup::set_Overlap(int8_t value)=0
```

## Açıklamalar

* -100%: Azami boşluk (çubuklar tamamen ayrılmıştır).
* 0%: Çubuklar yan yana, örtüşme veya boşluk olmadan yerleştirilir.
* 100%: Azami örtüşme (çubuklar birbirinin tamamen üstüne gelir). Bu özellik okunur/yazılabilir **int8_t**.



Aşağıdaki örnek, bir çizelge serisi grubu için örtüşmenin nasıl ayarlanacağını ve ortaya çıkan çizelgenin bir formda nasıl görüntüleneceğini gösterir: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Örtüşmeyi %55 olarak ayarla

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```


## Ayrıca Bak

* Sınıf [IChartSeriesGroup](../)
* İsim Uzayı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)