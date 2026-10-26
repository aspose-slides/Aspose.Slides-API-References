---
title: GetRange()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o intervalo de dados do gráfico.
type: docs
weight: 170
url: /pt/aspose.slides.charts/ichartdata/getrange/
---
## IChartData::GetRange() method


Obtém o intervalo de dados do gráfico.

```cpp
virtual System::String Aspose::Slides::Charts::IChartData::GetRange()=0
```


### Valor de Retorno

Fórmula do intervalo de dados das células. Ex.: \"Sheet1!$A$1:$C$4\"
## Observações




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 100.0f, 100.0f, 500.0f, 400.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Ver Também

* Classe [String](../../../system/string/)
* Classe [IChartData](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)