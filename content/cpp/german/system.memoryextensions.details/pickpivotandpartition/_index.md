---
title: PickPivotAndPartition()
second_title: Aspose.Slides für C++ API-Referenz
description: Wählt einen Pivot aus und partitioniert Schlüssel-Wert-Paare für Quicksort.
type: docs
weight: 105
url: /de/system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) Funktion

Wählt einen Pivot aus und partitioniert Schlüssel-Wert-Paare für Quicksort.

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| TKey | Der Typ der Schlüssel |
| TValue | Der Typ der Werte |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Der Span der zu partitionierenden Schlüssel |
| values | [Span](../../system/span/)\<TValue\>\& | Der Span der zu partitionierenden Werte |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/)-Funktion für Schlüssel |

### Rückgabewert

Der Pivot-Index nach dem Partitionieren

## Siehe auch

* Klasse [Span](../../system/span/)
* Namensraum [System::MemoryExtensions::Details](../)
* Bibliothek [Aspose.Slides](../../)