---
title: AddClone()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una copia della riga modello specificata e la inserisce nella parte inferiore di una tabella.
type: docs
weight: 53
url: /it/aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) metodo

Crea una copia della riga modello specificata e la inserisce nella parte inferiore di una tabella.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) che è usato come modello. |
| withAttachedColumns | **bool** | True per copiare anche tutte le colonne collegate alla riga modello. |

### Valore di ritorno

Colonne aggiunte.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IColumn](../../icolumn/)
* Classe [ColumnCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)