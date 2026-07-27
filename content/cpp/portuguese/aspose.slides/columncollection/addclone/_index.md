---
title: AddClone()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma cópia da linha modelo especificada e a insere na parte inferior de uma tabela.
type: docs
weight: 53
url: /pt/aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) method

Cria uma cópia da linha modelo especificada e a insere na parte inferior de uma tabela.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) que é usado como modelo. |
| withAttachedColumns | **bool** | True para copiar também todas as colunas anexadas à linha modelo. |

### Valor de Retorno

Colunas adicionadas.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IColumn](../../icolumn/)
* Classe [ColumnCollection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)