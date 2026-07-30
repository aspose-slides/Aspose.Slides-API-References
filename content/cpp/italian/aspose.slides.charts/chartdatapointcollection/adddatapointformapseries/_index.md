---
title: AddDataPointForMapSeries()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea il nuovo punto dati e lo aggiunge alla fine della raccolta. Applicabile alle serie il cui tipo di grafico è Map.
type: docs
weight: 417
url: /it/aspose.slides.charts/chartdatapointcollection/adddatapointformapseries/
---
## ChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr\<IChartDataCell\>) metodo

Crea il nuovo punto dati e lo aggiunge alla fine della raccolta. Applicabile alle serie il cui tipo di grafico è Map.

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForMapSeries(System::SharedPtr<IChartDataCell> value) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Punto dati ColorValue |

### Valore di ritorno

Nuovo punto dati.

## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Map, 50.0f, 50.0f, 500.0f, 400.0f, false);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();

auto series = chart->get_ChartData()->get_Series()->Add(Aspose::Slides::Charts::ChartType::Map);
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B2", System::ObjectExt::Box<int32_t>(5)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B3", System::ObjectExt::Box<int32_t>(1)));
series->get_DataPoints()->AddDataPointForMapSeries(wb->GetCell(0, u"B4", System::ObjectExt::Box<int32_t>(10)));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataPoint](../../ichartdatapoint/)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [ChartDataPointCollection](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)