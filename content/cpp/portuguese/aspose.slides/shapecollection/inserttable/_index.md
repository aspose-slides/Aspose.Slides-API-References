---
title: InsertTable()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma nova tabela e a insere na coleção de formas no índice especificado.
type: docs
weight: 482
url: /pt/aspose.slides/shapecollection/inserttable/
---
## ShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) método


Cria uma nova tabela e a insere na coleção de formas no índice especificado.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual a tabela será inserida. |
| x | **float** | A coordenada x da tabela, em pontos. |
| y | **float** | A coordenada y da tabela, em pontos. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Um array de doubles representando as larguras das colunas da tabela, em pontos. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Um array de doubles representando as alturas das linhas da tabela, em pontos. |

### Valor de Retorno

O [ITable](../../itable/) recém-criado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ITable](../../itable/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)