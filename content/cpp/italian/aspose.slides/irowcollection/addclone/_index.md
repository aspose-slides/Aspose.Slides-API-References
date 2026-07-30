---
title: AddClone()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una copia della riga modello specificata e la inserisce alla fine di una tabella.
type: docs
weight: 14
url: /it/aspose.slides/irowcollection/addclone/
---
## IRowCollection::AddClone(System::SharedPtr\<IRow\>, bool) metodo

Crea una copia della riga modello specificata e la inserisce alla fine di una tabella.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) che viene usato come modello. |
| withAttachedRows | **bool** | True per copiare anche tutte le righe collegate alla riga modello. |

### Valore restituito

Righe aggiunte.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IRow](../../irow/)
* Classe [IRowCollection](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)