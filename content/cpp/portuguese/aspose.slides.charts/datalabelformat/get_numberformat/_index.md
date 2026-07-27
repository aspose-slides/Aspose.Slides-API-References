---
title: get_NumberFormat()
second_title: Referência da API Aspose.Slides for C++
description: "Representa a string de formato para o objeto DataLabels. Leia System::String."
type: docs
weight: 27
url: /pt/aspose.slides.charts/datalabelformat/get_numberformat/
---
## DataLabelFormat::get_NumberFormat() método

Representa a string de formato para o objeto DataLabels. Leia [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_NumberFormat() override
```

## Observações

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```



Se o pai deste objeto [DataLabelFormat](../) for uma coleção [DataLabelCollection](../../datalabelcollection/) de rótulos de dados, então esta propriedade obtém ou define o valor padrão da propriedade NumberFormat para os novos rótulos de dados na coleção [DataLabelCollection](../../datalabelcollection/). Quando esta propriedade é definida com um valor, esse valor também é definido para a propriedade NumberFormat de todos os rótulos de dados na coleção [DataLabelCollection](../../datalabelcollection/) (isto é, \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" faz com que todos DataLabels[i].NumberFormat sejam iguais a val).

## Veja Também

* Classe [String](../../../system/string/)
* Classe [DataLabelFormat](../)
* Namespace [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)