---
title: AddDataPointForMapSeries()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Harita tipi olan seriler için uygulanabilir.
type: docs
weight: 417
url: /tr/aspose.slides.charts/chartdatapointcollection/adddatapointformapseries/
---
## ChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr\<IChartDataCell\>) yöntemi

Yeni veri noktasını oluşturur ve koleksiyonun sonuna ekler. Harita tipi olan seriler için uygulanabilir.

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr<IChartDataCell> value) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Veri noktası ColorValue |

## Dönüş Değeri

Yeni veri noktası.

## Açıklamalar

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Map, 50.0f, 50.0f, 500.0f, 400.0f, false);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();

auto series = chart->get_ChartData()->get_Series()->Add(Aspose::Slides::Charts::ChartType::Map);
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B2", System::ObjectExt::Box<int32_t>(5)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B3", System::ObjectExt::Box<int32_t>(1)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B4", System::ObjectExt::Box<int32_t>(10)));
```

## Ayrıca Bakınız

* TipTanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IChartDataPoint](../../ichartdatapoint/)
* Sınıf [IChartDataCell](../../ichartdatacell/)
* Sınıf [ChartDataPointCollection](../)
* İsimUzayı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)