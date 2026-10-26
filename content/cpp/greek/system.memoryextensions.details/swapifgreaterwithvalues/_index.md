---
title: SwapIfGreaterWithValues()
second_title: Aspose.Slides για το C++ API Αναφορά
description: Ανταλλάγει ζεύγη κλειδιού-τιμής εάν πληρούται η συνθήκη σύγκρισης.
type: docs
weight: 53
url: /el/system.memoryextensions.details/swapifgreaterwithvalues/
---"}
## System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>, int32_t, int32_t) συνάρτηση

Ανταλλάζει ζεύγη κλειδιού-τιμής εάν πληρούται η συνθήκη σύγκρισης.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer, int32_t i, int32_t j)
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| TKey | Ο τύπος των κλειδιών |
| TValue | Ο τύπος των τιμών |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Το εύρος των κλειδιών |
| values | [Span](../../system/span/)\<TValue\>\& | Το εύρος των τιμών |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) λειτουργία για κλειδιά |
| i | **int32_t** | Πρώτος δείκτης για σύγκριση |
| j | **int32_t** | Δεύτερος δείκτης για σύγκριση |

## Δείτε επίσης

* Κλάση [Span](../../system/span/)
* Χώρος ονομάτων [System::MemoryExtensions::Details](../)
* Βιβλιοθήκη [Aspose.Slides](../../)