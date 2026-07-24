---
title: CheckDiffForAll()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft, ob alle Sammlungselemente dem Prädikat entsprechen.
type: docs
weight: 14
url: /de/system/collectionasserthelper/checkdiffforall/
---
## CollectionAssertHelper::CheckDiffForAll(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) Methode

Überprüft, ob alle Sammlungselemente dem Prädikat entsprechen.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAll(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Prädikat zum Überprüfen. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Werte zum Überprüfen. |

### Rückgabewert

False, wenn die Überprüfung für ein beliebiges Element fehlschlägt, true, wenn alle bestehen.

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [ICollection](../../../system.collections.generic/icollection/)
* Struktur [CollectionAssertHelper](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)