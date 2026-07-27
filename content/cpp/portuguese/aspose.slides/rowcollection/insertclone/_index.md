---
title: InsertClone()
second_title: Aspose.Slides para C++ Referência da API
description: Cria uma cópia da linha modelo especificada e a insere na posição especificada em uma tabela.
type: docs
weight: 66
url: /pt/aspose.slides/rowcollection/insertclone/
---
## RowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) método


Cria uma cópia da linha modelo especificada e a insere na posição especificada em uma tabela.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | Índice de uma nova linha. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) que é usado como modelo. |
| withAttachedRows | **bool** | True para copiar também todas as linhas anexadas à linha de modelo. |

### Valor de Retorno

Linhas inseridas.

## Ver também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IRow](../../irow/)
* Classe [RowCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)