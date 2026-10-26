---
title: GetChildRows()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft Zeilen ab, die durch die angegebene Relation als Kind betrachtet werden.
type: docs
weight: 27
url: /de/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows(const System::SharedPtr\<System::Data::DataRelation\>\&) Methode

Ruft Zeilen ab, die durch die angegebene Relation als Kind betrachtet werden.

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| relation | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Data::DataRelation](../../datarelation/)\>\& | Relationsobjekt, um die Eltern-Zeile-zu-Kind-Zeile-Relation festzulegen. |

### Rückgabewert

[Array](../../../system/array/) der abgerufenen Kindzeilen.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [DataRow](../)
* Klasse [DataRelation](../../datarelation/)
* Namensraum [System::Data](../../)
* Bibliothek [Aspose.Slides](../../../)