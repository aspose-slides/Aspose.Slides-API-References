---
title: GetRange()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o intervalo de dados do gráfico.
type: docs
weight: 157
url: /pt/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() método


Obtém o intervalo de dados do gráfico.

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```


### Valor de Retorno

Fórmula do intervalo de dados das células. Ex.: \"Sheet1!$A$1:$C$4\"
## Observações




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## Veja Também

* Classe [String](../../../system/string/)
* Classe [ChartData](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)