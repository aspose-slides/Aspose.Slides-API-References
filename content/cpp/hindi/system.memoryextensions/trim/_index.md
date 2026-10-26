---
title: Trim()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक टाइप्ड स्पैन के दोनों सिरों से निर्दिष्ट तत्व को ट्रिम करता है।
type: docs
weight: 365
url: /hi/system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) function

एक टाइप्ड स्पैन के दोनों सिरों से निर्दिष्ट तत्व को ट्रिम करता है।

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ट्रिम करने के लिए स्पैन |
| trimElement | T | ट्रिम करने का तत्व |

### रिटर्न वैल्यू

दोनों सिरों से निर्दिष्ट तत्व ट्रिम किया हुआ नया स्पैन

## System::MemoryExtensions::Trim(Span\<T\>\&, T) function

एक परिवर्तनशील टाइप्ड स्पैन के दोनों सिरों से निर्दिष्ट तत्व को ट्रिम करता है।

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | ट्रिम करने के लिए परिवर्तनशील स्पैन |
| trimElement | T | ट्रिम करने का तत्व |

### रिटर्न वैल्यू

दोनों सिरों से निर्दिष्ट तत्व ट्रिम किया हुआ नया स्पैन

## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

एक टाइप्ड स्पैन के दोनों सिरों से निर्दिष्ट तत्वों को ट्रिम करता है।

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ट्रिम करने के लिए स्पैन |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ट्रिम करने वाले तत्व |

### रिटर्न वैल्यू

दोनों सिरों से निर्दिष्ट तत्वों ट्रिम किया हुआ नया स्पैन

## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

एक परिवर्तनशील टाइप्ड स्पैन के दोनों सिरों से निर्दिष्ट तत्वों को ट्रिम करता है।

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | ट्रिम करने के लिए परिवर्तनशील स्पैन |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ट्रिम करने वाले तत्व |

### रिटर्न वैल्यू

दोनों सिरों से निर्दिष्ट तत्वों ट्रिम किया हुआ नया स्पैन

## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) function

एक कैरेक्टर स्पैन के दोनों सिरों से व्हाइटस्पेस अक्षरों को ट्रिम करता है।

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | ट्रिम करने के लिए कैरेक्टर स्पैन |

### रिटर्न वैल्यू

दोनों सिरों से व्हाइटस्पेस ट्रिम किया हुआ नया स्पैन

## System::MemoryExtensions::Trim(Span\<char16_t\>\&) function

एक परिवर्तनशील कैरेक्टर स्पैन के दोनों सिरों से व्हाइटस्पेस अक्षरों को ट्रिम करता है।

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | ट्रिम करने के लिए परिवर्तनशील कैरेक्टर स्पैन |

### रिटर्न वैल्यू

दोनों सिरों से व्हाइटस्पेस ट्रिम किया हुआ नया स्पैन

## संबंधित देखें

* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* क्लास [Span](../../system/span/)
* नेमस्पेस [System::MemoryExtensions](../)
* लाइब्रेरी [Aspose.Slides](../../)