---
title: Overlaps()
second_title: Aspose.Slides for C++ API रेफ़रेंस
description: बिना ऑफ़सेट की गणना किए दो ReadOnlySpans मेमोरी में ओवरलैप होते हैं या नहीं निर्धारित करता है।
type: docs
weight: 274
url: /hi/system.memoryextensions/overlaps/
---
## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन

यह निर्धारित करता है कि दो ReadOnlySpans मेमोरी में ओवरलैप करते हैं या नहीं, बिना ऑफ़सेट की गणना किए।

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### टेम्पलेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ओवरलैप की जाँच के लिए पहला स्पैन |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ओवरलैप की जाँच के लिए दूसरा स्पैन |

### वापसी मान

यदि स्पैन्स में कोई सामान्य मेमोरी स्थान साझा हो तो true, अन्यथा false

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन

निर्धारित करता है कि [Span](../../system/span/) और [ReadOnlySpan](../../system/readonlyspan/) मेमोरी में ओवरलैप करते हैं या नहीं, बिना ऑफ़सेट की गणना किए।

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### टेम्पलेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) को ओवरलैप की जाँच के लिए |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) को ओवरलैप की जाँच के लिए |

### वापसी मान

यदि स्पैन्स में कोई सामान्य मेमोरी स्थान साझा हो तो true, अन्यथा false

## System::MemoryExtensions::Overlaps(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) फ़ंक्शन

निर्धारित करता है कि दो ReadOnlySpans मेमोरी में ओवरलैप करते हैं और ऑफ़सेट की गणना करता है।

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### टेम्पलेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ओवरलैप की जाँच के लिए पहला स्पैन |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ओवरलैप की जाँच के लिए दूसरा स्पैन |
| elementOffset | **int32_t**\& | यदि स्पैन्स ओवरलैप करते हैं तो उनके बीच का ऑफ़सेट प्राप्त करने वाला आउटपुट पैरामीटर |

### वापसी मान

यदि स्पैन्स में कोई सामान्य मेमोरी स्थान साझा हो तो true, अन्यथा false

## System::MemoryExtensions::Overlaps(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, int32_t\&) फ़ंक्शन

निर्धारित करता है कि [Span](../../system/span/) और [ReadOnlySpan](../../system/readonlyspan/) मेमोरी में ओवरलैप करते हैं और ऑफ़सेट की गणना करता है।

```cpp
template<typename T> bool System::MemoryExtensions::Overlaps(const Span<T> &span, const ReadOnlySpan<T> &other, int32_t &elementOffset)
```

### टेम्पलेट पैरामीटर

| परामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) को ओवरलैप की जाँच के लिए |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) को ओवरलैप की जाँच के लिए |
| elementOffset | **int32_t**\& | यदि स्पैन्स ओवरलैप करते हैं तो उनके बीच का ऑफ़सेट प्राप्त करने वाला आउटपुट पैरामीटर |

### वापसी मान

यदि स्पैन्स में कोई सामान्य मेमोरी स्थान साझा हो तो true, अन्यथा false

## देखें

* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* क्लास [Span](../../system/span/)
* नेमस्पेस [System::MemoryExtensions](../)
* लाइब्रेरी [Aspose.Slides](../../)