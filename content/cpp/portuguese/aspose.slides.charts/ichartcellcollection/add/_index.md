---
title: Add()
second_title: Aspose.Slides para Referência da API C++
description: Adiciona nova célula à coleção.
type: docs
weight: 53
url: /pt/aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) method

Adiciona nova célula à coleção.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Nova célula a ser adicionada. |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) method

Cria [IChartDataCell](../../ichartdatacell/) a partir do valor especificado e o adiciona à coleção.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | O valor. |

## Remarks

Este método adiciona a planilha com o nome AUTO_DATA e adiciona todos os valores lá. Se você usar [IChartDataWorkbook](../../ichartdataworkbook/) para adicionar ou editar valores [Cell](../../../aspose.slides/cell/), certifique-se de que não utiliza esta planilha. O número máximo de valores adicionados usando este método não deve exceder 16711680

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [IChartCellCollection](../)
* Classe [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)