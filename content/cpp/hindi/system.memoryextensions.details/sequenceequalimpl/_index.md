---
title: SequenceEqualImpl()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्थितियों से शुरू करके दो स्पैन्स समान हैं या नहीं जाँचता है।
type: docs
weight: 27
url: /hi/system.memoryextensions.details/sequenceequalimpl/
---
## System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan\<T\>\&, const int32_t, int32_t, const ReadOnlySpan\<T\>\&) फ़ंक्शन

Checks if two spans are equal starting from specified positions.

```cpp
template<typename T> bool System::MemoryExtensions::Details::SequenceEqualImpl(const ReadOnlySpan<T> &first, const int32_t start, int32_t length, const ReadOnlySpan<T> &second)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | Type of elements in spans |

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | First span |
| start | const **int32_t** | Starting index in first span |
| length | **int32_t** | Number of elements to compare |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Second span |

### वापसी मान

true if the specified ranges are equal, false otherwise

## संबंधित देखें

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions::Details](../)
* Library [Aspose.Slides](../../)