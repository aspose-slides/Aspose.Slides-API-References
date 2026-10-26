---
title: AddClone()
second_title: Aspose.Slides para C++ Referência da API
description: Cria uma cópia da linha modelo especificada e a insere na parte inferior de uma tabela.
type: docs
weight: 53
url: /pt/aspose.slides/rowcollection/addclone/
---
## RowCollection::AddClone(System::SharedPtr\<IRow\>, bool) método

Cria uma cópia da linha modelo especificada e a insere na parte inferior de uma tabela.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) que é usado como modelo. |
| withAttachedRows | **bool** | True para copiar também todas as linhas anexadas à linha modelo. |

### Return Value

Linhas adicionadas.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IRow](../../irow/)
* Classe [RowCollection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)