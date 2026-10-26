---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Se a categoria existir na coleção, retorne-a. Caso contrário, cria uma nova categoria de gráfico a partir de IChartDataCell e a adiciona à coleção.
type: docs
weight: 92
url: /pt/aspose.slides.charts/chartcategorycollection/add/
---
## ChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) método


Se a categoria existir na coleção, retorne-a. Caso contrário, cria nova categoria de gráfico a partir de [IChartDataCell](../../ichartdatacell/) e a adiciona à coleção.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) usado para criar a categoria de gráfico. |

### Valor de retorno

Categoria adicionada ou existente.



## ChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) método


Cria novo [ChartCategory](../../chartcategory/) a partir do valor e o adiciona à coleção.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<System::Object> value) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | O valor. |

### Valor de retorno

[IChartCategory](../../ichartcategory/) adicionado.
## Observações



Este método adiciona uma planilha com o nome AUTO_DATA e adiciona todos os valores nela. Se você usar [ChartDataWorkbook](../../chartdataworkbook/) para adicionar ou editar valores de células, certifique-se de que não utiliza esta planilha. O número máximo de valores adicionados usando este método não deve exceder 16711680



## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartCategory](../../ichartcategory/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [ChartCategoryCollection](../)
* Class [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)