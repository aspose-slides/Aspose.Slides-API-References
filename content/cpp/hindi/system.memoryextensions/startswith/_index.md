---
title: StartsWith()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: जाँचता है कि क्या स्पैन निर्दिष्ट मान से शुरू होता है।
type: docs
weight: 352
url: /hi/system.memoryextensions/startswith/
---
## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const T\&) function

स्पैन यह जांचता है कि क्या निर्दिष्ट मान से शुरू होता है।

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const T &value)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | जाँचने के लिए स्पैन |
| value | const T\& | स्पैन की शुरुआत में जांचने के लिए मान |

### वापसी मान

स्पैन यदि मान से शुरू होता है तो true, अन्यथा false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

स्पैन यह जांचता है कि क्या निर्दिष्ट मान स्पैन से शुरू होता है।

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | जाँचने के लिए स्पैन |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | शुरुआत में जांचने के लिए मानों वाला स्पैन |

### वापसी मान

स्पैन यदि मान स्पैन से शुरू होता है तो true, अन्यथा false

## System::MemoryExtensions::StartsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

परिवर्तनीय स्पैन यह जांचता है कि क्या निर्दिष्ट केवल-पढ़ने-योग्य मान स्पैन से शुरू होता है।

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | जाँचने के लिए परिवर्तनीय स्पैन |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | जाँचने के लिए केवल-पढ़ने-योग्य मान स्पैन |

### वापसी मान

स्पैन यदि मान स्पैन से शुरू होता है तो true, अन्यथा false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) function

केवल-पढ़ने-योग्य स्पैन यह जांचता है कि क्या निर्दिष्ट परिवर्तनीय मान स्पैन से शुरू होता है।

```cpp
template<typename T> bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | जाँचने के लिए केवल-पढ़ने-योग्य स्पैन |
| value | const [Span](../../system/span/)\<T\>\& | जाँचने के लिए परिवर्तनीय मान स्पैन |

### वापसी मान

स्पैन यदि मान स्पैन से शुरू होता है तो true, अन्यथा false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

अक्षर स्पैन यह जांचता है कि क्या स्ट्रिंग तुलना का उपयोग करके निर्दिष्ट मान स्पैन से शुरू होता है।

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | जाँचने के लिए अक्षर स्पैन |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | जाँचने के लिए मानों वाला अक्षर स्पैन |
| comparisonType | [StringComparison](../../system/stringcomparison/) | करने के लिए स्ट्रिंग तुलना का प्रकार |

### वापसी मान

स्पैन यदि मान स्पैन से शुरू होता है तो true, अन्यथा false

## System::MemoryExtensions::StartsWith(const ReadOnlySpan\<String\>\&, const char16_t *) function

स्ट्रिंग स्पैन यह जांचता है कि क्या निर्दिष्ट अक्षर एरे से शुरू होता है।

```cpp
bool System::MemoryExtensions::StartsWith(const ReadOnlySpan<String> &span, const char16_t *val)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<[String](../../system/string/)\>\& | जाँचने के लिए स्ट्रिंग स्पैन |
| val | const char16_t * | शुरुआत में जांचने के लिए अक्षर एरे |

### वापसी मान

स्पैन यदि अक्षर एरे से शुरू होता है तो true, अन्यथा false

## संबंधित देखें

* एन्यूम [StringComparison](../../system/stringcomparison/)
* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* क्लास [Span](../../system/span/)
* क्लास [String](../../system/string/)
* नामस्थान [System::MemoryExtensions](../)
* लाइब्रेरी [Aspose.Slides](../../)