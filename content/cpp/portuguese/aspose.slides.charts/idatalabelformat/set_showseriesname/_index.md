---
title: set_ShowSeriesName()
second_title: Referência da API Aspose.Slides para C++
description: Define um Boolean para indicar o comportamento de exibição do nome da série nos rótulos de dados de um gráfico. True para mostrar o nome da série. False para ocultar. Escreva bool.
type: docs
weight: 183
url: /pt/aspose.slides.charts/idatalabelformat/set_showseriesname/
---
## IDataLabelFormat::set_ShowSeriesName(bool) método


Define um Boolean para indicar o comportamento de exibição do nome da série para os rótulos de dados em um gráfico. True para mostrar o nome da série. False para ocultar. Escreva **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowSeriesName(bool value)=0
```

## Observações


Se o pai deste objeto [DataLabelFormat](../../datalabelformat/) for uma coleção [DataLabelCollection](../../datalabelcollection/) de rótulos de dados, então esta propriedade obtém ou define o valor padrão da propriedade ShowSeriesName para os novos rótulos de dados na coleção [DataLabelCollection](../../datalabelcollection/). Definir esta propriedade com um valor também define esse valor para a propriedade ShowSeriesName de todos os rótulos de dados na coleção [DataLabelCollection](../../datalabelcollection/) (ou seja, "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" faz com que todos DataLabels[i].ShowSeriesName sejam iguais a val). 



## Veja Também

* Classe [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)