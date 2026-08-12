---
title: TrimStart()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक टाइप्ड स्पैन की शुरुआत से निर्दिष्ट तत्व को ट्रिम करता है।
type: docs
weight: 391
url: /hi/system.memoryextensions/trimstart/
---
## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const T\&) फ़ंक्शन

एक टाइप्ड स्पैन की शुरुआत से निर्दिष्ट तत्व को ट्रिम करता है।

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const T &trimElement)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ट्रिम करने के लिए स्पैन |
| trimElement | const T\& | ट्रिम करने के लिए तत्व |

### वापसी मान

निर्दिष्ट तत्व को शुरुआत से हटाए हुए नया स्पैन

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const T\&) फ़ंक्शन

परिवर्तनीय टाइप्ड स्पैन की शुरुआत से निर्दिष्ट तत्व को ट्रिम करता है।

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const T &trimElement)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | ट्रिम करने के लिए परिवर्तनीय स्पैन |
| trimElement | const T\& | ट्रिम करने के लिए तत्व |

### वापसी मान

निर्दिष्ट तत्व को शुरुआत से हटाए हुए नया स्पैन

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन

एक टाइप्ड स्पैन की शुरुआत से निर्दिष्ट तत्वों को ट्रिम करता है।

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ट्रिम करने के लिए स्पैन |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ट्रिम करने के लिए तत्व |

### वापसी मान

निर्दिष्ट तत्वों को शुरुआत से हटाए हुए नया स्पैन

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन

परिवर्तनीय टाइप्ड स्पैन की शुरुआत से निर्दिष्ट तत्वों को ट्रिम करता है।

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | ट्रिम करने के लिए परिवर्तनीय स्पैन |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ट्रिम करने के लिए तत्व |

### वापसी मान

निर्दिष्ट तत्वों को शुरुआत से हटाए हुए नया स्पैन

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&) फ़ंक्शन

कैरेक्टर स्पैन की शुरुआत से खाली स्थान अक्षरों को ट्रिम करता है।

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | ट्रिम करने के लिए कैरेक्टर स्पैन |

### वापसी मान

खाली स्थान अक्षरों को शुरुआत से हटाए हुए नया स्पैन

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&) फ़ंक्शन

परिवर्तनीय कैरेक्टर स्पैन की शुरुआत से खाली स्थान अक्षरों को ट्रिम करता है।

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | ट्रिम करने के लिए परिवर्तनीय कैरेक्टर स्पैन |

### वापसी मान

खाली स्थान अक्षरों को शुरुआत से हटाए हुए नया स्पैन

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, char16_t) फ़ंक्शन

कैरेक्टर स्पैन की शुरुआत से निर्दिष्ट अक्षर को ट्रिम करता है।

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | ट्रिम करने के लिए कैरेक्टर स्पैन |
| trimchar | char16_t | ट्रिम करने के लिए अक्षर |

### वापसी मान

निर्दिष्ट अक्षर को शुरुआत से हटाए हुए नया स्पैन

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, char16_t) फ़ंक्शन

परिवर्तनीय कैरेक्टर स्पैन की शुरुआत से निर्दिष्ट अक्षर को ट्रिम करता है।

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, char16_t trimchar)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | ट्रिम करने के लिए परिवर्तनीय कैरेक्टर स्पैन |
| trimchar | char16_t | ट्रिम करने के लिए अक्षर |

### वापसी मान

निर्दिष्ट अक्षर को शुरुआत से हटाए हुए नया स्पैन

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) फ़ंक्शन

कैरेक्टर स्पैन की शुरुआत से निर्दिष्ट अक्षरों को ट्रिम करता है।

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | ट्रिम करने के लिए कैरेक्टर स्पैन |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | ट्रिम करने के लिए अक्षर |

### वापसी मान

निर्दिष्ट अक्षरों को शुरुआत से हटाए हुए नया स्पैन

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) फ़ंक्शन

परिवर्तनीय कैरेक्टर स्पैन की शुरुआत से निर्दिष्ट अक्षरों को ट्रिम करता है।

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | ट्रिम करने के लिए परिवर्तनीय कैरेक्टर स्पैन |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | ट्रिम करने के लिए अक्षर |

### वापसी मान

निर्दिष्ट अक्षरों को शुरुआत से हटाए हुए नया स्पैन

## देखें

* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* क्लास [Span](../../system/span/)
* नेमस्पेस [System::MemoryExtensions](../)
* लाइब्रेरी [Aspose.Slides](../../)