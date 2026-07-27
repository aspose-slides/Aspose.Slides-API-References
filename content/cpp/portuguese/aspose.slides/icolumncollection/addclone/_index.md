---
title: AddClone()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma cópia da linha de modelo especificada e a insere na parte inferior de uma tabela.
type: docs
weight: 14
url: /pt/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) método


Cria uma cópia da linha de modelo especificada e a insere na parte inferior de uma tabela.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) que é usado como modelo. |
| withAttachedColumns | **bool** | True para copiar também todas as colunas anexadas à linha de modelo. |

### Return Value

Colunas adicionadas.

## Ver também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IColumn](../../icolumn/)
* Classe [IColumnCollection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)