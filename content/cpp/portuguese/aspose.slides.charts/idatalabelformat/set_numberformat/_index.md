---
title: set_NumberFormat()
second_title: Referência da API Aspose.Slides para C++
description: "Representa a string de formato para o objeto DataLabels. Use System::String."
type: docs
weight: 40
url: /pt/aspose.slides.charts/idatalabelformat/set_numberformat/
---
## IDataLabelFormat::set_NumberFormat(System::String) método

Representa a string de formato para o objeto DataLabels. Escreva [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_NumberFormat(System::String value)=0
```

## Observações

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

Se o pai deste objeto [DataLabelFormat](../../datalabelformat/) for uma coleção [DataLabelCollection](../../datalabelcollection/) de rótulos de dados, então esta propriedade obtém ou define o valor padrão da propriedade NumberFormat para os novos rótulos de dados na coleção [DataLabelCollection](../../datalabelcollection/). Quando esta propriedade é definida com um valor, esse valor também é definido para a propriedade NumberFormat de todos os rótulos de dados na coleção [DataLabelCollection](../../datalabelcollection/) (ou seja, "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" faz com que todos DataLabels[i].NumberFormat sejam iguais a val).

## Ver Também

* Classe [String](../../../system/string/)
* Classe [IDataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)