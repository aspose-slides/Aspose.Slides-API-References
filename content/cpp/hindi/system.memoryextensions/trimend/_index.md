---
title: TrimEnd()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक टाइप्ड स्पैन के अंत से निर्दिष्ट तत्व को ट्रिम करता है।
type: docs
weight: 378
url: /hi/system.memoryextensions/trimend/
---
## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const T\&) फ़ंक्शन

एक टाइप्ड स्पैन के अंत से निर्दिष्ट तत्व को ट्रिम करता है।

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const T &trimElement)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ट्रिम करने हेतु स्पैन |
| trimElement | const T\& | ट्रिम करने हेतु तत्व |

### वापसी मान

अंत में से निर्दिष्ट तत्व को ट्रिम किए हुए नया स्पैन

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const T\&) फ़ंक्शन

परिवर्तनीय टाइप्ड स्पैन के अंत से निर्दिष्ट तत्व को ट्रिम करता है।

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const T &trimElement)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | ट्रिम करने हेतु परिवर्तनीय स्पैन |
| trimElement | const T\& | ट्रिम करने हेतु तत्व |

### वापसी मान

अंत में से निर्दिष्ट तत्व को ट्रिम किए हुए नया स्पैन

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन

एक टाइप्ड स्पैन के अंत से निर्दिष्ट तत्वों को ट्रिम करता है।

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ट्रिम करने हेतु स्पैन |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ट्रिम करने हेतु तत्व |

### वापसी मान

अंत में से निर्दिष्ट तत्वों को ट्रिम किए हुए नया स्पैन

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन

परिवर्तनीय टाइप्ड स्पैन के अंत से निर्दिष्ट तत्वों को ट्रिम करता है।

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | ट्रिम करने हेतु परिवर्तनीय स्पैन |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ट्रिम करने हेतु तत्व |

### वापसी मान

अंत में से निर्दिष्ट तत्वों को ट्रिम किए हुए नया स्पैन

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&) फ़ंक्शन

एक कैरेक्टर स्पैन के अंत से खाली स्थान के अक्षरों को ट्रिम करता है।

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | ट्रिम करने हेतु कैरेक्टर स्पैन |

### वापसी मान

अंत में से खाली स्थान के अक्षरों को ट्रिम किए हुए नया स्पैन

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&) फ़ंक्शन

परिवर्तनीय कैरेक्टर स्पैन के अंत से खाली स्थान के अक्षरों को ट्रिम करता है।

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | ट्रिम करने हेतु परिवर्तनीय कैरेक्टर स्पैन |

### वापसी मान

अंत में से खाली स्थान के अक्षरों को ट्रिम किए हुए नया स्पैन

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, char16_t) फ़ंक्शन

एक कैरेक्टर स्पैन के अंत से निर्दिष्ट अक्षर को ट्रिम करता है।

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | ट्रिम करने हेतु कैरेक्टर स्पैन |
| trimchar | char16_t | ट्रिम करने हेतु अक्षर |

### वापसी मान

अंत में से निर्दिष्ट अक्षर को ट्रिम किए हुए नया स्पैन

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, char16_t) फ़ंक्शन

परिवर्तनीय कैरेक्टर स्पैन के अंत से निर्दिष्ट अक्षर को ट्रिम करता है।

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, char16_t trimchar)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | ट्रिम करने हेतु परिवर्तनीय कैरेक्टर स्पैन |
| trimchar | char16_t | ट्रिम करने हेतु अक्षर |

### वापसी मान

अंत में से निर्दिष्ट अक्षर को ट्रिम किए हुए नया स्पैन

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) फ़ंक्शन

एक कैरेक्टर स्पैन के अंत से निर्दिष्ट अक्षरों को ट्रिम करता है।

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimChars)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | ट्रिम करने हेतु कैरेक्टर स्पैन |
| trimChars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | ट्रिम करने हेतु अक्षर |

### वापसी मान

अंत में से निर्दिष्ट अक्षरों को ट्रिम किए हुए नया स्पैन

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) फ़ंक्शन

परिवर्तनीय कैरेक्टर स्पैन के अंत से निर्दिष्ट अक्षरों को ट्रिम करता है।

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | ट्रिम करने हेतु परिवर्तनीय कैरेक्टर स्पैन |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | ट्रिम करने हेतु अक्षर |

### वापसी मान

अंत में से निर्दिष्ट अक्षरों को ट्रिम किए हुए नया स्पैन

## संबंधित देखें

* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* क्लास [Span](../../system/span/)
* नेमस्पेस [System::MemoryExtensions](../)
* लाइब्रेरी [Aspose.Slides](../../)