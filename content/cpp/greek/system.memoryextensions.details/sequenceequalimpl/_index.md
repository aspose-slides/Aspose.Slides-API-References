---
title: SequenceEqualImpl()
second_title: Aspose.Slides για την αναφορά API του C++
description: Ελέγχει αν δύο spans είναι ίσα ξεκινώντας από τις καθορισμένες θέσεις.
type: docs
weight: 27
url: /el/system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) function


Ελέγχει εάν δύο spans είναι ίσα ξεκινώντας από τις καθορισμένες θέσεις.

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```


### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| T | Type of elements in spans |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | First span |
| start | const **int32_t** | Starting index in first span |
| length | **int32_t** | Number of elements to compare |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Second span |

### Τιμή επιστροφής

true αν τα καθορισμένα ranges είναι ίσα, false otherwise

## Δείτε επίσης

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)