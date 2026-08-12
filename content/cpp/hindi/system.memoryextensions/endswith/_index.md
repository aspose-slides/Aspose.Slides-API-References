---
title: EndsWith()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्धारित करता है कि क्या ReadOnlySpan<T> किसी एकल मान पर समाप्त होता है।
type: docs
weight: 131
url: /hi/system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) function

निर्धारित करता है कि क्या ReadOnlySpan<T> किसी एकल मान पर समाप्त होता है।

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | जाँच करने के लिए स्पैन |
| value | const T\& | स्पैन के अंत में जाँचने के लिए मान |

### रिटर्न मान

यदि स्पैन मान के साथ समाप्त होता है तो true, अन्यथा false

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

निर्धारित करता है कि क्या ReadOnlySpan<T> किसी अन्य ReadOnlySpan<T> पर समाप्त होता है।

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | जाँच करने के लिए स्पैन |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | लक्ष्य स्पैन के अंत में जाँचने के लिए स्पैन |

### रिटर्न मान

यदि स्पैन मान स्पैन के साथ समाप्त होता है तो true, अन्यथा false

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

निर्धारित करता है कि क्या Span<T> किसी ReadOnlySpan<T> पर समाप्त होता है।

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | जाँच करने के लिए स्पैन |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | लक्ष्य स्पैन के अंत में जाँचने के लिए स्पैन |

### रिटर्न मान

यदि स्पैन मान स्पैन के साथ समाप्त होता है तो true, अन्यथा false

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) function

निर्धारित करता है कि क्या ReadOnlySpan<T> किसी Span<T> पर समाप्त होता है।

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | जाँच करने के लिए स्पैन |
| value | const [Span](../../system/span/)\<T\>\& | लक्ष्य स्पैन के अंत में जाँचने के लिए स्पैन |

### रिटर्न मान

यदि स्पैन मान स्पैन के साथ समाप्त होता है तो true, अन्यथा false

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) function

निर्धारित करता है कि क्या Span<T> किसी अन्य Span<T> पर समाप्त होता है।

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | जाँच करने के लिए स्पैन |
| value | const [Span](../../system/span/)\<T\>\& | लक्ष्य स्पैन के अंत में जाँचने के लिए स्पैन |

### रिटर्न मान

यदि स्पैन मान स्पैन के साथ समाप्त होता है तो true, अन्यथा false

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

निर्धारित करता है कि क्या ReadOnlySpan<char16_t> निर्दिष्ट मान पर StringComparison का उपयोग करके समाप्त होता है।

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | जाँच करने के लिए स्पैन |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | स्पैन के अंत में जाँचने के लिए मान |
| comparisonType | [StringComparison](../../system/stringcomparison/) | उपयोग करने के लिए स्ट्रिंग तुलना प्रकार |

### रिटर्न मान

यदि स्पैन मान के साथ समाप्त होता है तो true, अन्यथा false

## देखें

* Enum [StringComparison](../../system/stringcomparison/)
* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* क्लास [Span](../../system/span/)
* नेमस्पेस [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)