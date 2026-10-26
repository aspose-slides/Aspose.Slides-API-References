---
title: InsertClone()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una copia della riga modello specificata e la inserisce nella posizione specificata in una tabella.
type: docs
weight: 66
url: /it/aspose.slides/rowcollection/insertclone/
---
## RowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) metodo


Crea una copia della riga modello specificata e la inserisce nella posizione specificata in una tabella.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Indice di una nuova riga. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) che è usato come modello. |
| withAttachedRows | **bool** | True per copiare anche tutte le righe collegate alla riga modello. |

### Valore di ritorno

Righe inserite.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IRow](../../irow/)
* Classe [RowCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)