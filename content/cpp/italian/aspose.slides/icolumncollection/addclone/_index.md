---
title: AddClone()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una copia della riga modello specificata e la inserisce in fondo a una tabella.
type: docs
weight: 14
url: /it/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) method


Crea una copia della riga modello specificata e la inserisce in fondo a una tabella.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
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
* Class [IColumn](../../icolumn/)
* Class [IColumnCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)