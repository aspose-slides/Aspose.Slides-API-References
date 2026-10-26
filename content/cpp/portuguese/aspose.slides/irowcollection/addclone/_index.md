---
title: AddClone()
second_title: Aspose.Slides para C++ Referência da API
description: Cria uma cópia da linha modelo especificada e a insere na parte inferior de uma tabela.
type: docs
weight: 14
url: /pt/aspose.slides/irowcollection/addclone/
---
## IRowCollection::AddClone(System::SharedPtr\<IRow\>, bool) método

Cria uma cópia da linha modelo especificada e a insere na parte inferior de uma tabela.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) que é usado como modelo. |
| withAttachedRows | **bool** | True para copiar também todas as linhas anexadas à linha modelo. |

### Valor de retorno

Linhas adicionadas.

## Veja também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IRow](../../irow/)
* Classe [IRowCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)