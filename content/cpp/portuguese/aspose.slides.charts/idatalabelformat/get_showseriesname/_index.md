---
title: get_ShowSeriesName()
second_title: Aspose.Slides para C++ Referência da API
description: Retorna um Boolean para indicar o comportamento de exibição do nome da série para os rótulos de dados em um gráfico. Verdadeiro para exibir o nome da série. Falso para ocultar. Leitura bool.
type: docs
weight: 170
url: /pt/aspose.slides.charts/idatalabelformat/get_showseriesname/
---
## IDataLabelFormat::get_ShowSeriesName() método

Retorna um Boolean para indicar o comportamento de exibição do nome da série para os rótulos de dados em um gráfico. Verdadeiro para exibir o nome da série. Falso para ocultar. Leitura **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowSeriesName()=0
```

## Observações

Se o pai deste objeto [DataLabelFormat](../../datalabelformat/) for uma coleção [DataLabelCollection](../../datalabelcollection/) de rótulos de dados, então esta propriedade obtém ou define o valor padrão da propriedade ShowSeriesName para os novos rótulos de dados na coleção [DataLabelCollection](../../datalabelcollection/). Definir esta propriedade com um valor também define esse valor na propriedade ShowSeriesName para todos os rótulos de dados na coleção [DataLabelCollection](../../datalabelcollection/) (ou seja, "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" faz com que todos DataLabels[i].ShowSeriesName seja igual a val). 

## Ver Também

* Classe [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)