---
title: PickPivotAndPartition()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιλέγει άξονα και διαχωρίζει ζεύγη κλειδιού-τιμής για γρήγορη ταξινόμηση.
type: docs
weight: 105
url: /el/system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) συνάρτηση

Επιλέγει άξονα και διαμερίζει ζεύγη κλειδιού-τιμής για γρήγορη ταξινόμηση.

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TKey | Ο τύπος των κλειδιών |
| TValue | Ο τύπος των τιμών |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Το εύρος των κλειδιών για διαμερισμό |
| values | [Span](../../system/span/)\<TValue\>\& | Το εύρος των τιμών για διαμερισμό |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) συνάρτηση για κλειδιά |

### Τιμή επιστροφής

Ο δείκτης άξονα μετά το διαμερισμό

## Δείτε επίσης

* Κλάση [Span](../../system/span/)
* Χώρος ονομάτων [System::MemoryExtensions::Details](../)
* Βιβλιοθήκη [Aspose.Slides](../../)