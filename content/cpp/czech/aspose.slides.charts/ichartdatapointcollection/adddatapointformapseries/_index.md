---
title: AddDataPointForMapSeries()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž typ grafu je Map.
type: docs
weight: 352
url: /cs/aspose.slides.charts/ichartdatapointcollection/adddatapointformapseries/
---
## IChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr\<IChartDataCell\>) method


Vytvoří nový datový bod a přidá jej na konec kolekce. Použitelné pro řady, jejichž typ grafu je Map.

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr<IChartDataCell> value)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Data point ColorValue |

### Návratová hodnota

Nový datový bod.
## Poznámky




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Map, 50.0f, 50.0f, 500.0f, 400.0f, false);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();

auto series = chart->get_ChartData()->get_Series()->Add(Aspose::Slides::Charts::ChartType::Map);
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B2", System::ObjectExt::Box<int32_t>(5)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B3", System::ObjectExt::Box<int32_t>(1)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B4", System::ObjectExt::Box<int32_t>(10)));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IChartDataPoint](../../ichartdatapoint/)
* Třída [IChartDataCell](../../ichartdatacell/)
* Třída [IChartDataPointCollection](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)