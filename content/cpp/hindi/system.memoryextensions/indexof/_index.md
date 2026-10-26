---
title: IndexOf()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: दूसरे ReadOnlySpan<T> में ReadOnlySpan<T> मान का इंडेक्स खोजता है
type: docs
weight: 144
url: /hi/system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन

ReadOnlySpan<T> मान का इंडेक्स दूसरे ReadOnlySpan<T> में खोजता है

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोजने के लिए स्पैन |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोजने के लिए स्पैन |

### रिटर्न वैल्यू

पहले प्रकट होने का शून्य-आधारित इंडेक्स, या यदि नहीं मिला तो -1

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) फ़ंक्शन

ReadOnlySpan<T> में एकल मान का इंडेक्स खोजता है

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोजने के लिए स्पैन |
| value | const T\& | खोजने के लिए मान |

### रिटर्न वैल्यू

पहले प्रकट होने का शून्य-आधारित इंडेक्स, या यदि नहीं मिला तो -1

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन

Span<T> में ReadOnlySpan<T> मान का इंडेक्स खोजता है

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | खोजने के लिए स्पैन |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोजने के लिए स्पैन |

### रिटर्न वैल्यू

पहले प्रकट होने का शून्य-आधारित इंडेक्स, या यदि नहीं मिला तो -1

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) फ़ंक्शन

Span<T> में एकल मान का इंडेक्स खोजता है

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | खोजने के लिए स्पैन |
| value | const T\& | खोजने के लिए मान |

### रिटर्न वैल्यू

पहले प्रकट होने का शून्य-आधारित इंडेक्स, या यदि नहीं मिला तो -1

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) फ़ंक्शन

StringComparison के साथ ReadOnlySpan<char16_t> में ReadOnlySpan<char16_t> मान का इंडेक्स खोजता है।

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | खोजने के लिए स्पैन |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | खोजने के लिए मान |
| comparisonType | [StringComparison](../../system/stringcomparison/) | उपयोग करने के लिए स्ट्रिंग तुलना प्रकार |

### रिटर्न वैल्यू

पहले प्रकट होने का शून्य-आधारित इंडेक्स, या यदि नहीं मिला तो -1

## देखें

* एनम [StringComparison](../../system/stringcomparison/)
* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* क्लास [Span](../../system/span/)
* नामस्थान [System::MemoryExtensions](../)
* लाइब्रेरी [Aspose.Slides](../../)