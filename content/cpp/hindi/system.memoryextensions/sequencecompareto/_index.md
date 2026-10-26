---
title: SequenceCompareTo()
second_title: Aspose.Slides for C++ API संदर्भ
description: दो ReadOnlySpans की लेक्सिकोग्राफ़िक तुलना करता है।
type: docs
weight: 313
url: /hi/system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन


दो ReadOnlySpans की लेक्सिकोग्राफ़िक तुलना करता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | पहला स्पैन जिसे तुलना किया जाता है |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | दूसरा स्पैन जिसे तुलना किया जाता है |

### रिटर्न मान

- 1 यदि span < other, 0 यदि span == other, 1 यदि span > other

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन


[Span](../../system/span/) और [ReadOnlySpan](../../system/readonlyspan/) की लेक्सिकोग्राफ़िक तुलना करता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) की तुलना |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) की तुलना |

### रिटर्न मान

- 1 यदि span < other, 0 यदि span == other, 1 यदि span > other

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) फ़ंक्शन


[ReadOnlySpan](../../system/readonlyspan/) और [Span](../../system/span/) की लेक्सिकोग्राफ़िक तुलना करता है।

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```


### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) की तुलना |
| other | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) की तुलना |

### रिटर्न मान

- 1 यदि span < other, 0 यदि span == other, 1 यदि span > other

## देखें भी

* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* क्लास [Span](../../system/span/)
* नामस्थान [System::MemoryExtensions](../)
* लाइब्रेरी [Aspose.Slides](../../)