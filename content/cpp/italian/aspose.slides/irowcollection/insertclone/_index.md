---
title: InsertClone()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una copia della riga modello specificata e la inserisce nella posizione specificata in una tabella.
type: docs
weight: 27
url: /it/aspose.slides/irowcollection/insertclone/
---
## IRowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) metodo

Crea una copia della riga modello specificata e la inserisce nella posizione specificata in una tabella.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Indice di una nuova riga. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) che è usato come modello. |
| withAttachedRows | **bool** | True per copiare anche tutte le righe collegate alla riga modello. |

### Valore restituito

Righe inserite.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IRow](../../irow/)
* Classe [IRowCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)