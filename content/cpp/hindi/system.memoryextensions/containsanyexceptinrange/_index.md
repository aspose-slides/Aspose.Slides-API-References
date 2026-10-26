---
title: ContainsAnyExceptInRange()
second_title: Aspose.Slides for C++ API संदर्भ
description: जाँचता है कि क्या रीड-ओनली स्पैन निर्दिष्ट सीमा के बाहर कोई तत्व रखता है।
type: docs
weight: 79
url: /hi/system.memoryextensions/containsanyexceptinrange/
---
## System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

जाँचता है कि क्या रीड-ओनली स्पैन निर्दिष्ट सीमा के बाहर कोई तत्व रखता है।

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार (समानता योग्य होना चाहिए) |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोज करने के लिये स्पैन |
| lowInclusive | const T\& | निचली सीमा (शामिल) |
| highInclusive | const T\& | ऊपरी सीमा (शामिल) |

### रिटर्न मान

यदि सीमा के बाहर कोई तत्व पाया जाता है तो true, अन्यथा false

## System::MemoryExtensions::ContainsAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) function

जाँचता है कि क्या परिवर्तनशील स्पैन निर्दिष्ट सीमा के बाहर कोई तत्व रखता है।

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार (समानता योग्य होना चाहिए) |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | खोज करने के लिये परिवर्तनशील स्पैन |
| lowInclusive | const T\& | निचली सीमा (शामिल) |
| highInclusive | const T\& | ऊपरी सीमा (शामिल) |

### रिटर्न मान

यदि सीमा के बाहर कोई तत्व पाया जाता है तो true, अन्यथा false

## See Also

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)