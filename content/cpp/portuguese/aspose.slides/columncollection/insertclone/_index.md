---
title: InsertClone()
second_title: Aspose.Slides para C++ - Referência da API
description: Cria uma cópia da coluna modelo especificada e a insere na posição especificada em uma tabela.
type: docs
weight: 66
url: /pt/aspose.slides/columncollection/insertclone/
---
## ColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) method

Cria uma cópia da coluna modelo especificada e a insere na posição especificada em uma tabela.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Índice de uma nova coluna. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) que é usada como modelo. |
| withAttachedColumns | **bool** | True para copiar também todas as colunas anexadas à coluna modelo. |

### Valor de Retorno

Colunas inseridas.

## Ver também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IColumn](../../icolumn/)
* Classe [ColumnCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)