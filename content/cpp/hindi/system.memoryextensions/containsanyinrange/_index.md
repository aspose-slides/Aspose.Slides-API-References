---
title: ContainsAnyInRange()
second_title: Aspose.Slides for C++ एपीआई संदर्भ
description: जाँचता है कि क्या एक read-only span निर्दिष्ट रेंज के भीतर कोई तत्व रखता है।
type: docs
weight: 92
url: /hi/system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) फ़ंक्शन

जाँचता है कि क्या एक read-only span निर्दिष्ट रेंज के भीतर कोई तत्व रखता है।

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार (समानता के लिए तुल्य होना चाहिए) |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोज के लिए स्पैन |
| lowInclusive | const T\& | न्यूनतम सीमा (समावेशी) |
| highInclusive | const T\& | अधिकतम सीमा (समावेशी) |

### वापसी मान

यदि रेंज के भीतर कोई तत्व पाया जाता है तो true, अन्यथा false

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) फ़ंक्शन

जाँचता है कि क्या एक mutable span निर्दिष्ट रेंज के भीतर कोई तत्व रखता है।

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार (समानता के लिए तुल्य होना चाहिए) |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | खोज के लिए mutable स्पैन |
| lowInclusive | const T\& | न्यूनतम सीमा (समावेशी) |
| highInclusive | const T\& | अधिकतम सीमा (समावेशी) |

### वापसी मान

यदि रेंज के भीतर कोई तत्व पाया जाता है तो true, अन्यथा false

## देखें भी

* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* क्लास [Span](../../system/span/)
* नेमस्पेस [System::MemoryExtensions](../)
* लाइब्रेरी [Aspose.Slides](../../)