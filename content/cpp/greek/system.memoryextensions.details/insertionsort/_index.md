---
title: InsertionSort()
second_title: Aspose.Slides για C++ API Reference
description: Εκτελεί ταξινόμηση εισαγωγής σε ζεύγη κλειδιού-τιμής.
type: docs
weight: 66
url: /el/system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) συνάρτηση

Εκτελεί ταξινόμηση εισαγωγής σε ζεύγη κλειδιού-τιμής.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TKey | Ο τύπος των κλειδιών |
| TValue | Ο τύπος των τιμών |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Το εύρος των κλειδιών προς ταξινόμηση |
| values | [Span](../../system/span/)\<TValue\>\& | Το εύρος των τιμών προς ταξινόμηση |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) συνάρτηση για κλειδιά |

## Δείτε επίσης

* Κλάση [Span](../../system/span/)
* Χώρος ονομάτων [System::MemoryExtensions::Details](../)
* Βιβλιοθήκη [Aspose.Slides](../../)