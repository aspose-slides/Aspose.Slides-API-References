---
title: AsSpan()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक ऐरे से एक स्पैन बनाता है।
type: docs
weight: 1
url: /hi/system.memoryextensions/asspan/
---
## System::MemoryExtensions::AsSpan(const ArrayPtr\<T\>\&, int32_t, int32_t) फ़ंक्शन

एक ऐरे से एक स्पैन बनाता है।

```cpp
template<typename T> Span<T> System::MemoryExtensions::AsSpan(const ArrayPtr<T> &array, int32_t start=0, int32_t length=-1)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | ऐरे में तत्वों का प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | स्रोत ऐरे। |
| start | **int32_t** | ऐरे में प्रारंभिक सूचकांक। |
| length | **int32_t** | स्पैन की लंबाई। |

### वापसी मान

Span<T> निर्दिष्ट भाग के ऐरे को स्पैन करता है।

## System::MemoryExtensions::AsSpan(const String\&, int32_t, int32_t) फ़ंक्शन

एक स्ट्रिंग से केवल-पठन योग्य स्पैन बनाता है।

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::AsSpan(const String &text, int32_t start=0, int32_t length=-1)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | const [String](../../system/string/)\& | स्रोत स्ट्रिंग। |
| start | **int32_t** | स्ट्रिंग में प्रारंभिक सूचकांक। |
| length | **int32_t** | स्पैन की लंबाई। |

### वापसी मान

ReadOnlySpan<char16_t> निर्दिष्ट भाग के स्ट्रिंग को स्पैन करता है।

## संबंधित देखें

* Typedef [ArrayPtr](../../system/arrayptr/)
* क्लास [Span](../../system/span/)
* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* क्लास [String](../../system/string/)
* नामस्थान [System::MemoryExtensions](../)
* लाइब्रेरी [Aspose.Slides](../../)