---
title: InsertClone()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma cópia da coluna modelo especificada e a insere na posição especificada em uma tabela.
type: docs
weight: 27
url: /pt/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) método


Cria uma cópia da coluna modelo especificada e a insere na posição especificada em uma tabela.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Índice de uma nova coluna. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) que é usado como modelo. |
| withAttachedColumns | **bool** | Verdadeiro para copiar também todas as colunas anexadas à coluna modelo. |

### Valor de Retorno

Colunas inseridas.

## Ver Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IColumn](../../icolumn/)
* Classe [IColumnCollection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)