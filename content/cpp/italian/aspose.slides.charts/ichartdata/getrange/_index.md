---
title: GetRange()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene l'intervallo dei dati del grafico.
type: docs
weight: 170
url: /it/aspose.slides.charts/ichartdata/getrange/
---
## IChartData::GetRange() metodo


Ottiene l'intervallo dati del grafico.

```cpp
virtual System::String Aspose::Slides::Charts::IChartData::GetRange()=0
```


### Valore restituito

Formula dell'intervallo dati delle celle. Per esempio: "Sheet1!$A$1:$C$4"
## Osservazioni




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 100.0f, 100.0f, 500.0f, 400.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [IChartData](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)