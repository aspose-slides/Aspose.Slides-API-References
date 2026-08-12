---
title: LastIndexOfAny()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: स्पैन के भीतर तीन निर्दिष्ट मानों में से किसी एक की अंतिम आवृत्ति को खोजता है।
type: docs
weight: 222
url: /hi/system.memoryextensions/lastindexofany/
---
## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) फ़ंक्शन

तीन निर्दिष्ट मानों में से किसी एक की स्पैन के भीतर अंतिम आवृत्ति को खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | वह स्पैन जिसके भीतर खोज करनी है |
| value0 | const T\& | पहला मान जिसके लिए खोजनी है |
| value1 | const T\& | दूसरा मान जिसके लिए खोजनी है |
| value2 | const T\& | तीसरा मान जिसके लिए खोजनी है |

### रिटर्न वैल्यू

अंतिम आवृत्ति का शून्य-आधारित इंडेक्स, या यदि न मिला हो तो -1

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&, const T\&) फ़ंक्शन

तीन निर्दिष्ट मानों में से किसी एक की परिवर्तनशील स्पैन के भीतर अंतिम आवृत्ति को खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | वह स्पैन जिसके भीतर खोज करनी है |
| value0 | const T\& | पहला मान जिसके लिए खोजनी है |
| value1 | const T\& | दूसरा मान जिसके लिए खोजनी है |
| value2 | const T\& | तीसरा मान जिसके लिए खोजनी है |

### रिटर्न वैल्यू

अंतिम आवृत्ति का शून्य-आधारित इंडेक्स, या यदि न मिला हो तो -1

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) फ़ंक्शन

दो निर्दिष्ट मानों में से किसी एक की स्पैन के भीतर अंतिम आवृत्ति को खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | वह स्पैन जिसके भीतर खोज करनी है |
| value0 | const T\& | पहला मान जिसके लिए खोजनी है |
| value1 | const T\& | दूसरा मान जिसके लिए खोजनी है |

### रिटर्न वैल्यू

अंतिम आवृत्ति का शून्य-आधारित इंडेक्स, या यदि न मिला हो तो -1

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const T\&, const T\&) फ़ंक्शन

दो निर्दिष्ट मानों में से किसी एक की परिवर्तनशील स्पैन के भीतर अंतिम आवृत्ति को खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const T &value0, const T &value1)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | वह स्पैन जिसके भीतर खोज करनी है |
| value0 | const T\& | पहला मान जिसके लिए खोजनी है |
| value1 | const T\& | दूसरा मान जिसके लिए खोजनी है |

### रिटर्न वैल्यू

अंतिम आवृत्ति का शून्य-आधारित इंडेक्स, या यदि न मिला हो तो -1

## System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन

एक अनुक्रम से किसी भी मान की स्पैन के भीतर अंतिम आवृत्ति को खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | वह स्पैन जिसके भीतर खोज करनी है |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोजने के लिए मानों की अनुक्रमिका |

### रिटर्न वैल्यू

अंतिम आवृत्ति का शून्य-आधारित इंडेक्स, या यदि न मिला हो तो -1

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन

एक अनुक्रम से किसी भी मान की परिवर्तनशील स्पैन के भीतर अंतिम आवृत्ति को खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | वह स्पैन जिसके भीतर खोज करनी है |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोजने के लिए मानों की अनुक्रमिका |

### रिटर्न वैल्यू

अंतिम आवृत्ति का शून्य-आधारित इंडेक्स, या यदि न मिला हो तो -1

## System::MemoryExtensions::LastIndexOfAny(const Span\<T\>\&, const Span\<T\>\&) फ़ंक्शन

परिवर्तनशील अनुक्रम से किसी भी मान की परिवर्तनशील स्पैन के भीतर अंतिम आवृत्ति को खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAny(const Span<T> &span, const Span<T> &values)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | वह स्पैन जिसके भीतर खोज करनी है |
| values | const [Span](../../system/span/)\<T\>\& | खोजने के लिए मानों की अनुक्रमिका |

### रिटर्न वैल्यू

अंतिम आवृत्ति का शून्य-आधारित इंडेक्स, या यदि न मिला हो तो -1

## See Also

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)