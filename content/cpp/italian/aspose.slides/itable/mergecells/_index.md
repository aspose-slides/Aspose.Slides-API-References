---
title: MergeCells()
second_title: Riferimento API di Aspose.Slides per C++
description: Unisce le celle vicine.
type: docs
weight: 261
url: /it/aspose.slides/itable/mergecells/
---
## ITable::MergeCells(System::SharedPtr\<ICell\>, System::SharedPtr\<ICell\>, bool) metodo

Unisce le celle vicine.

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITable::MergeCells(System::SharedPtr<ICell> cell1, System::SharedPtr<ICell> cell2, bool allowSplitting)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cell1 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) da unire. |
| cell2 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) da unire. |
| allowSplitting | **bool** | True per consentire la divisione delle celle. |

### Valore di ritorno

Cella unita.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICell](../../icell/)
* Class [ITable](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)