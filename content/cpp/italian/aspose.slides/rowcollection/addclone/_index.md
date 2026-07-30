---
title: AddClone()
second_title: Riferimento API Aspose.Slides per C++
description: Crea una copia della riga modello specificata e la inserisce nella parte inferiore di una tabella.
type: docs
weight: 53
url: /it/aspose.slides/rowcollection/addclone/
---
## RowCollection::AddClone(System::SharedPtr\<IRow\>, bool) metodo

Crea una copia della riga modello specificata e la inserisce nella parte inferiore di una tabella.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) che viene usato come modello. |
| withAttachedRows | **bool** | True per copiare anche tutte le righe collegate alla riga modello. |

### Valore di ritorno

Righe aggiunte.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IRow](../../irow/)
* Classe [RowCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)