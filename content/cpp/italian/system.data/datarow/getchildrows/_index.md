---
title: GetChildRows()
second_title: Riferimento API Aspose.Slides per C++
description: Ottiene le righe che sono considerate figlie tramite la relazione specificata.
type: docs
weight: 27
url: /it/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows(const System::SharedPtr\<System::Data::DataRelation\>\&) metodo

Ottiene le righe che sono considerate figlie tramite la relazione specificata.

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| relation | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Data::DataRelation](../../datarelation/)\>\& | Oggetto relazione per specificare la relazione riga padre - riga figlia. |

### Valore di ritorno

[Array](../../../system/array/) di righe figlie recuperate.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [DataRow](../)
* Classe [DataRelation](../../datarelation/)
* Spazio dei nomi [System::Data](../../)
* Libreria [Aspose.Slides](../../../)