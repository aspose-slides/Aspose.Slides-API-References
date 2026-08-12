---
title: LastIndexOf()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: एक स्पैन के भीतर अनुक्रम का अंतिम उदाहरण खोजता है।
type: docs
weight: 209
url: /hi/system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन


एक स्पैन के भीतर अनुक्रम का अंतिम उदाहरण खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोज हेतु स्पैन |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोजा जाने वाला अनुक्रम |

### रिटर्न मान

अंतिम उदाहरण का शून्य-आधारित इंडेक्स, या यदि नहीं मिला तो -1

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) फ़ंक्शन


एक स्पैन के भीतर एकल मान का अंतिम उदाहरण खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोज हेतु स्पैन |
| value | const T\& | खोजा जाने वाला मान |

### रिटर्न मान

अंतिम उदाहरण का शून्य-आधारित इंडेक्स, या यदि नहीं मिला तो -1

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन


एक परिवर्तनीय स्पैन के भीतर अनुक्रम का अंतिम उदाहरण खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | खोज हेतु स्पैन |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोजा जाने वाला अनुक्रम |

### रिटर्न मान

अंतिम उदाहरण का शून्य-आधारित इंडेक्स, या यदि नहीं मिला तो -1

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) फ़ंक्शन


परिवर्तनीय स्पैन के भीतर एकल मान का अंतिम उदाहरण खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | खोज हेतु स्पैन |
| value | const T\& | खोजा जाने वाला मान |

### रिटर्न मान

अंतिम उदाहरण का शून्य-आधारित इंडेक्स, या यदि नहीं मिला तो -1

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) फ़ंक्शन


निर्दिष्ट स्ट्रिंग तुलना का उपयोग करके स्पैन के भीतर मान का अंतिम उदाहरण खोजता है।

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | खोज हेतु स्पैन |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | खोजा जाने वाला मान |
| comparisonType | [StringComparison](../../system/stringcomparison/) | किया जाने वाला स्ट्रिंग तुलना प्रकार |

### रिटर्न मान

अंतिम उदाहरण का शून्य-आधारित इंडेक्स, या यदि नहीं मिला तो -1

## देखें

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)