---
title: InsertClone()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma cópia da linha modelo especificada e a insere na posição especificada em uma tabela.
type: docs
weight: 27
url: /pt/aspose.slides/irowcollection/insertclone/
---
## IRowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) método


Cria uma cópia da linha modelo especificada e a insere na posição especificada em uma tabela.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Índice de uma nova linha. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) que é usado como modelo. |
| withAttachedRows | **bool** | True para copiar também todas as linhas anexadas à linha modelo. |

### Valor de retorno

Linhas inseridas.

## Veja também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IRow](../../irow/)
* Classe [IRowCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)