---
title: Add()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona nova célula à coleção.
type: docs
weight: 53
url: /pt/aspose.slides.charts/chartcellcollection/add/
---
## ChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) método

Adiciona nova célula à coleção.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<IChartDataCell> cell) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Nova célula a ser adicionada. |

## ChartCellCollection::Add(System::SharedPtr\<System::Object\>) método

Cria [ChartDataCell](../../chartdatacell/) a partir do valor especificado e o adiciona à coleção.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<System::Object> value) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | O valor. |

## Observações

Este método adiciona a planilha com o nome AUTO_DATA e adiciona todos os valores lá. Se você usar [ChartDataWorkbook](../../chartdataworkbook/) para adicionar ou editar valores [Cell](../../../aspose.slides/cell/), certifique-se de que não use esta planilha. O número máximo de valores adicionados usando este método não deve exceder 16711680

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [ChartCellCollection](../)
* Classe [Object](../../../system/object/)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)