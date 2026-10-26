---
title: get_Separator()
second_title: Aspose.Slides para C++ Referência da API
description: "Define ou retorna um Variant que representa o separador usado para os rótulos de dados em um gráfico. Leia System::String."
type: docs
weight: 326
url: /pt/aspose.slides.charts/idatalabelformat/get_separator/
---
## IDataLabelFormat::get_Separator() método

Define ou retorna um Variant que representa o separador usado para os rótulos de dados em um gráfico. Leia [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_Separator()=0
```

## Observações

Se o pai deste objeto [DataLabelFormat](../../datalabelformat/) for uma coleção [DataLabelCollection](../../datalabelcollection/) de rótulos de dados, então esta propriedade obtém ou define o valor padrão da propriedade Separator para os novos rótulos de dados na coleção [DataLabelCollection](../../datalabelcollection/). Definir esta propriedade com um valor também define esse valor na propriedade Separator para todos os rótulos de dados na coleção [DataLabelCollection](../../datalabelcollection/) (ou seja, "DataLabels.DefaultDataLabelFormat.Separator = val;" faz com que todos DataLabels[i].Separator sejam iguais a val).

## Ver Também

* Classe [String](../../../system/string/)
* Classe [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)