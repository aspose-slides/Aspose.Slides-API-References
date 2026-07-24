---
title: CheckDiffForAny()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft, ob irgendein Element der Sammlung das Prädikat erfüllt.
type: docs
weight: 27
url: /de/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) Methode

Überprüft, ob irgendein Element der Sammlung das Prädikat erfüllt.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Zu prüfendes Prädikat. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Zu prüfende Werte. |

### Rückgabewert

Wahr, wenn die Prüfung für irgendein Element erfolgreich ist, sonst falsch, wenn alle bestehen.

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [ICollection](../../../system.collections.generic/icollection/)
* Struktur [CollectionAssertHelper](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)