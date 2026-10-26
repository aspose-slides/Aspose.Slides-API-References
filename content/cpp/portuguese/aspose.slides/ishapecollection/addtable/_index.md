---
title: AddTable()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma nova tabela e a adiciona ao final da coleção de formas.
type: docs
weight: 430
url: /pt/aspose.slides/ishapecollection/addtable/
---
## IShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) método

Cria uma nova tabela e a adiciona ao final da coleção de formas.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada x da tabela, em pontos. |
| y | **float** | A coordenada y da tabela, em pontos. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Um array de doubles representando as larguras das colunas da tabela, em pontos. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Um array de doubles representando as alturas das linhas da tabela, em pontos. |

### Valor de Retorno

O [ITable](../../itable/) recém-criado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ITable](../../itable/)
* Classe [IShapeCollection](../)
* namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)