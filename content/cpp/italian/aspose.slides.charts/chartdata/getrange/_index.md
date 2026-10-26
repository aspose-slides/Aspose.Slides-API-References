---
title: GetRange()
second_title: Aspose.Slides per C++ Riferimento API
description: Ottiene l'intervallo dei dati del grafico.
type: docs
weight: 157
url: /it/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() metodo

Ottiene l'intervallo dei dati del grafico.

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```

### Valore restituito

Formula dell'intervallo dei dati delle celle. Ad esempio: "Sheet1!$A$1:$C$4"

## Osservazioni


```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [ChartData](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)