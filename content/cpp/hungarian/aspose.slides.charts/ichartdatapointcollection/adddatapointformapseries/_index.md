---
title: AddDataPointForMapSeries()
second_title: Aspose.Slides C++ API referencia
description: Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható olyan sorozatokra, amelyek diagramtípusa Térkép.
type: docs
weight: 352
url: /hu/aspose.slides.charts/ichartdatapointcollection/adddatapointformapseries/
---
## IChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr\<IChartDataCell\>) metódus

Létrehozza az új adatpontot, és a gyűjtemény végére adja hozzá. Alkalmazható azon sorozatokra, amelyek diagramtípusa Térkép.

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr<IChartDataCell> value)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Data point ColorValue |

### Visszatérési érték

Új adatpont.
## Megjegyzések




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Map, 50.0f, 50.0f, 500.0f, 400.0f, false);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();

auto series = chart->get_ChartData()->get_Series()->Add(Aspose::Slides::Charts::ChartType::Map);
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B2", System::ObjectExt::Box<int32_t>(5)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B3", System::ObjectExt::Box<int32_t>(1)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B4", System::ObjectExt::Box<int32_t>(10)));
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IChartDataPoint](../../ichartdatapoint/)
* Osztály [IChartDataCell](../../ichartdatacell/)
* Osztály [IChartDataPointCollection](../)
* Névtér [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)