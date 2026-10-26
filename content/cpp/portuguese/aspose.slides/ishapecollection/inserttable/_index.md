---
title: InsertTable()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma nova tabela e a insere na coleção de formas no índice especificado.
type: docs
weight: 443
url: /pt/aspose.slides/ishapecollection/inserttable/
---
## IShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) método


Cria uma nova tabela e a insere na coleção de formas no índice especificado.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the table. |
| x | **float** | The x-coordinate of the table, in points. |
| y | **float** | The y-coordinate of the table, in points. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Um array de doubles que representa as larguras das colunas da tabela, em points. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Um array de doubles que representa as alturas das linhas da tabela, em points. |

### Valor de Retorno

O [ITable](../../itable/) recém-criado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ITable](../../itable/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)