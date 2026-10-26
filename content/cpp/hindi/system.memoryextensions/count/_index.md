---
title: Count()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: पढ़ने-केवल स्पैन में मान की उपस्थिति गिनता है।
type: docs
weight: 118
url: /hi/system.memoryextensions/count/
---
## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const T\&) फ़ंक्शन


पढ़ने-केवल स्पैन में मान की उपस्थिति गिनता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const T &value)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोज करने के लिए स्पैन |
| value | const T\& | गिनने के लिए मान |

### रिटर्न मान

स्पैन में मान के प्रकट होने की संख्या

## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन


एक पढ़ने-केवल स्पैन के भीतर दूसरे स्पैन की उपस्थिति गिनता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोज करने के लिए स्पैन |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | उपस्थिति गिनने के लिए स्पैन |

### रिटर्न मान

स्पैन में मान के प्रकट होने की संख्या

## System::MemoryExtensions::Count(const Span\<T\>\&, const T\&) फ़ंक्शन


Span<T> में एकल मान की उपस्थिति गिनता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const T &value)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | खोज करने के लिए स्पैन |
| value | const T\& | उपस्थिति गिनने के लिए मान |

### रिटर्न मान

स्पैन में मान की उपस्थिति की संख्या

## System::MemoryExtensions::Count(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन


Span<T> में ReadOnlySpan<T> की उपस्थिति गिनता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const ReadOnlySpan<T> &value)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | खोज करने के लिए स्पैन |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | मान स्पैन को गिनने वाले स्पैन |

### रिटर्न मान

लक्ष्य स्पैन में मान स्पैन की उपस्थितियों की संख्या

## संबंधित देखें

* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* क्लास [Span](../../system/span/)
* नेमस्पेस [System::MemoryExtensions](../)
* लाइब्रेरी [Aspose.Slides](../../)