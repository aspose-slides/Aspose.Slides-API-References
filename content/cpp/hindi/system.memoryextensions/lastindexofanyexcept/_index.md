---
title: LastIndexOfAnyExcept()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक span के भीतर तीन निर्दिष्ट मानों को छोड़कर किसी भी तत्व का अंतिम प्रकट होना खोजता है।
type: docs
weight: 235
url: /hi/system.memoryextensions/lastindexofanyexcept/
---
## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) फ़ंक्शन

एक span के भीतर तीन निर्दिष्ट मानों को छोड़कर किसी भी तत्व का अंतिम प्रकट होना खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोज के भीतर span |
| value0 | const T\& | बहिर्गत करने के लिये पहला मान |
| value1 | const T\& | बहिर्गत करने के लिये दूसरा मान |
| value2 | const T\& | बहिर्गत करने के लिये तीसरा मान |

### रिटर्न वैल्यू

अ-बहिर्गत तत्व का शून्य-आधारित सूचकांक, या यदि नहीं मिला तो -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) फ़ंक्शन

एक mutable span के भीतर तीन निर्दिष्ट मानों को छोड़कर किसी भी तत्व का अंतिम प्रकट होना खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | खोज के भीतर span |
| value0 | const T\& | बहिर्गत करने के लिये पहला मान |
| value1 | const T\& | बहिर्गत करने के लिये दूसरा मान |
| value2 | const T\& | बहिर्गत करने के लिये तीसरा मान |

### रिटर्न वैल्यू

अ-बहिर्गत तत्व का शून्य-आधारित सूचकांक, या यदि नहीं मिला तो -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) फ़ंक्शन

एक span के भीतर दो निर्दिष्ट मानों को छोड़कर किसी भी तत्व का अंतिम प्रकट होना खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोज के भीतर span |
| value0 | const T\& | बहिर्गत करने के लिये पहला मान |
| value1 | const T\& | बहिर्गत करने के लिये दूसरा मान |

### रिटर्न वैल्यू

अ-बहिर्गत तत्व का शून्य-आधारित सूचकांक, या यदि नहीं मिला तो -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&, const T\&) फ़ंक्शन

एक mutable span के भीतर दो निर्दिष्ट मानों को छोड़कर किसी भी तत्व का अंतिम प्रकट होना खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | खोज के भीतर span |
| value0 | const T\& | बहिर्गत करने के लिये पहला मान |
| value1 | const T\& | बहिर्गत करने के लिये दूसरा मान |

### रिटर्न वैल्यू

अ-बहिर्गत तत्व का शून्य-आधारित सूचकांक, या यदि नहीं मिला तो -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) फ़ंक्शन

एक span के भीतर एक निर्दिष्ट मान को छोड़कर किसी भी तत्व का अंतिम प्रकट होना खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोज के भीतर span |
| value | const T\& | बहिर्गत करने के लिये मान |

### रिटर्न वैल्यू

अ-बहिर्गत तत्व का शून्य-आधारित सूचकांक, या यदि नहीं मिला तो -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const T\&) फ़ंक्शन

एक mutable span के भीतर एक निर्दिष्ट मान को छोड़कर किसी भी तत्व का अंतिम प्रकट होना खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const T &value)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | खोज के भीतर span |
| value | const T\& | बहिर्गत करने के लिये मान |

### रिटर्न वैल्यू

अ-बहिर्गत तत्व का शून्य-आधारित सूचकांक, या यदि नहीं मिला तो -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन

एक span के भीतर एक अनुक्रम से मानों को छोड़कर किसी भी तत्व का अंतिम प्रकट होना खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोज के भीतर span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | बहिर्गत करने के लिये मानों का अनुक्रम |

### रिटर्न वैल्यू

अ-बहिर्गत तत्व का शून्य-आधारित सूचकांक, या यदि नहीं मिला तो -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन

एक mutable span के भीतर एक अनुक्रम से मानों को छोड़कर किसी भी तत्व का अंतिम प्रकट होना खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | खोज के भीतर span |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | बहिर्गत करने के लिये मानों का अनुक्रम |

### रिटर्न वैल्यू

अ-बहिर्गत तत्व का शून्य-आधारित सूचकांक, या यदि नहीं मिला तो -1

## System::MemoryExtensions::LastIndexOfAnyExcept(const Span\<T\>\&, const Span\<T\>\&) फ़ंक्शन

एक mutable span के भीतर एक mutable अनुक्रम से मानों को छोड़कर किसी भी तत्व का अंतिम प्रकट होना खोजता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExcept(const Span<T> &span, const Span<T> &values)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | खोज के भीतर span |
| values | const [Span](../../system/span/)\<T\>\& | बहिर्गत करने के लिये मानों का अनुक्रम |

### रिटर्न वैल्यू

अ-बहिर्गत तत्व का शून्य-आधारित सूचकांक, या यदि नहीं मिला तो -1

## देखे जाएँ

* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)