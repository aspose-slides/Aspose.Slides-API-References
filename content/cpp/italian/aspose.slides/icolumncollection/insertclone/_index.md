---
title: InsertClone()
second_title: Riferimento API Aspose.Slides per C++
description: Crea una copia della colonna modello specificata e la inserisce nella posizione specificata in una tabella.
type: docs
weight: 27
url: /it/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) metodo

Crea una copia della colonna modello specificata e la inserisce nella posizione specificata in una tabella.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index of a new column. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) che viene utilizzata come modello. |
| withAttachedColumns | **bool** | True to copy also all columns attached to the template column. |

### Valore di ritorno

Colonne inserite.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IColumn](../../icolumn/)
* Classe [IColumnCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)