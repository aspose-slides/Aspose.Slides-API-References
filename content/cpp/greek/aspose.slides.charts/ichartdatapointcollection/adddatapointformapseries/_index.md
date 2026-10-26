---
title: AddDataPointForMapSeries()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Ισχύει για σειρές των οποίων ο τύπος διαγράμματος είναι Map.
type: docs
weight: 352
url: /el/aspose.slides.charts/ichartdatapointcollection/adddatapointformapseries/
---
## IChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr\<IChartDataCell\>) μέθοδος


Δημιουργεί το νέο σημείο δεδομένων και το προσθέτει στο τέλος της συλλογής. Ισχύει για σειρές των οποίων ο τύπος διαγράμματος είναι Map.

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr<IChartDataCell> value)=0
```


### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | σημείο δεδομένων ColorValue |

### Τιμή επιστροφής

Νέο σημείο δεδομένων.

## Σχόλια




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Map, 50.0f, 50.0f, 500.0f, 400.0f, false);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();

auto series = chart->get_ChartData()->get_Series()->Add(Aspose::Slides::Charts::ChartType::Map);
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B2", System::ObjectExt::Box<int32_t>(5)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B3", System::ObjectExt::Box<int32_t>(1)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B4", System::ObjectExt::Box<int32_t>(10)));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IChartDataPoint](../../ichartdatapoint/)
* Κλάση [IChartDataCell](../../ichartdatacell/)
* Κλάση [IChartDataPointCollection](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)