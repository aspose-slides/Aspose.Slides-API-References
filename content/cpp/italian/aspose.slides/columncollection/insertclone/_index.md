---
title: InsertClone()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una copia della colonna modello specificata e la inserisce nella posizione specificata in una tabella.
type: docs
weight: 66
url: /it/aspose.slides/columncollection/insertclone/
---
## ColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) metodo

Crea una copia della colonna modello specificata e la inserisce nella posizione specificata in una tabella.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Indice di una nuova colonna. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) che è usato come modello. |
| withAttachedColumns | **bool** | True per copiare anche tutte le colonne collegate alla colonna modello. |

### Valore di ritorno

Colonne inserite.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IColumn](../../icolumn/)
* Classe [ColumnCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)