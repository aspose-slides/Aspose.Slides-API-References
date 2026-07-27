---
title: Add()
second_title: Referência da API Aspose.Slides for C++
description: Se a categoria existir na coleção, retorne-a. Caso contrário, cria uma nova categoria de gráfico a partir de IChartDataCell e a adiciona à coleção.
type: docs
weight: 53
url: /pt/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) método


Se a categoria existir na coleção, retorne-a. Caso contrário, cria uma nova categoria de gráfico a partir de [IChartDataCell](../../ichartdatacell/) e a adiciona à coleção.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) usado para criar a categoria de gráfico. |

### Valor de Retorno

Categoria adicionada ou existente.



## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) método


Cria um novo [IChartCategory](../../ichartcategory/) a partir do valor e o adiciona à coleção.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | O valor. |

### Valor de Retorno

[IChartCategory](../../ichartcategory/) adicionado.



## Observações



Este método adiciona uma planilha com o nome AUTO_DATA e adiciona todos os valores nela. Se você usar [IChartDataWorkbook](../../ichartdataworkbook/) para adicionar ou editar valores de células, certifique-se de que não use esta planilha. O número máximo de valores adicionados usando este método não deve exceder 16711680



## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartCategory](../../ichartcategory/)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [IChartCategoryCollection](../)
* Classe [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)