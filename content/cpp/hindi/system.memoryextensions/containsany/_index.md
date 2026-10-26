---
title: ContainsAny()
second_title: Aspose.Slides for C++ API संदर्भ
description: जाँचता है कि क्या एक read-only span में दो मानों में से कोई भी मौजूद है।
type: docs
weight: 53
url: /hi/system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) फ़ंक्शन

जाँचता है कि क्या एक read-only span में दो मानों में से कोई भी मौजूद है।

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोजने के लिए span |
| value0 | const T\& | ढूँढने के लिए पहला मान |
| value1 | const T\& | ढूँढने के लिए दूसरा मान |

### रिटर्न वैल्यू

यदि span में मानों में से कोई भी पाया जाता है तो true, अन्यथा false

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) फ़ंक्शन

जाँचता है कि क्या एक read-only span में तीन मानों में से कोई भी मौजूद है।

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोजने के लिए span |
| value0 | const T\& | ढूँढने के लिए पहला मान |
| value1 | const T\& | ढूँढने के लिए दूसरा मान |
| value2 | const T\& | ढूँढने के लिए तीसरा मान |

### रिटर्न वैल्यू

यदि span में मानों में से कोई भी पाया जाता है तो true, अन्यथा false

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) फ़ंक्शन

जाँचता है कि क्या एक mutable span में दो मानों में से कोई भी मौजूद है।

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | खोजने के लिए mutable span |
| value0 | const T\& | ढूँढने के लिए पहला मान |
| value1 | const T\& | ढूँढने के लिए दूसरा मान |

### रिटर्न वैल्यू

यदि span में मानों में से कोई भी पाया जाता है तो true, अन्यथा false

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) फ़ंक्शन

जाँचता है कि क्या एक mutable span में तीन मानों में से कोई भी मौजूद है।

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | खोजने के लिए mutable span |
| value0 | const T\& | ढूँढने के लिए पहला मान |
| value1 | const T\& | ढूँढने के लिए दूसरा मान |
| value2 | const T\& | ढूँढने के लिए तीसरा मान |

### रिटर्न वैल्यू

यदि span में मानों में से कोई भी पाया जाता है तो true, अन्यथा false

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन

जाँचता है कि क्या एक read-only span में किसी अन्य span से कोई भी मान मौजूद है।

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोजने के लिए span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ढूँढने के लिए मानों का span |

### रिटर्न वैल्यू

यदि span में values के किसी भी मान को पाया जाता है तो true, अन्यथा false

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन

जाँचता है कि क्या एक mutable span में किसी read-only span से कोई भी मान मौजूद है।

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | खोजने के लिए mutable span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | ढूँढने के लिए read-only span |

### रिटर्न वैल्यू

यदि span में values के किसी भी मान को पाया जाता है तो true, अन्यथा false

## देखें

* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* क्लास [Span](../../system/span/)
* नेमस्पेस [System::MemoryExtensions](../)
* लाइब्रेरी [Aspose.Slides](../../)