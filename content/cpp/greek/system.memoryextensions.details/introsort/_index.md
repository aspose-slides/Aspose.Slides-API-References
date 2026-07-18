---
title: IntroSort()
second_title: Aspose.Slides για C++ - Αναφορά API
description: Εσωτερική υλοποίηση αλγόριθμου introsort για ζεύγη κλειδιού-τιμής.
type: docs
weight: 40
url: /el/system.memoryextensions.details/introsort/
---
## System::MemoryExtensions::Details::IntroSort(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) function

Εσωτερική υλοποίηση αλγόριθμου introsort για ζεύγη κλειδιού-τιμής.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::IntroSort(Span<TKey> &keys, Span<TValue> &values, int32_t depthLimit, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| TKey | Ο τύπος των κλειδιών |
| TValue | Ο τύπος των τιμών |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | Το τμήμα των κλειδιών προς ταξινόμηση |
| values | [Span](../../system/span/)\<TValue\>\& | Το τμήμα των τιμών προς ταξινόμηση |
| depthLimit | **int32_t** | Μέγιστο βάθος επανάληψης πριν η εναλλαγή σε heapsort |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) συνάρτηση για κλειδιά |

## Δείτε επίσης

* Κλάση [Span](../../system/span/)
* Ονομαχώρος [System::MemoryExtensions::Details](../)
* Βιβλιοθήκη [Aspose.Slides](../../)