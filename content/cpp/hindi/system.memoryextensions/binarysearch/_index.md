---
title: BinarySearch()
second_title: Aspose.Slides for C++ API संदर्भ
description: सॉर्ट किए गए स्पैन पर बाइनरी खोज करता है।
type: docs
weight: 14
url: /hi/system.memoryextensions/binarysearch/
---
## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const TComparable\&) फ़ंक्शन

सॉर्टेड स्पैन पर बाइनरी खोज करता है।

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const TComparable &comparable)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | The type of elements in the span |
| TComparable | The type of the comparable value |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sorted span to search |
| comparable | const TComparable\& | The value to search for |

### रिटर्न वैल्यू

[Index](../../system/index/) पाए गए तत्व का, या यदि नहीं मिला तो insertion point का बिटवाइज़ कॉम्प्लीमेंट

## System::MemoryExtensions::BinarySearch(const ReadOnlySpan\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) फ़ंक्शन

कस्टम कंपेयर द्वारा सॉर्टेड स्पैन पर बाइनरी खोज करता है।

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const ReadOnlySpan<T> &span, const T &value, const SharedPtr<TComparer> &comparerPtr)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | The type of elements in the span |
| TComparer | The type of the comparer |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sorted span to search |
| value | const T\& | The value to search for |
| comparerPtr | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | The comparer to use for comparisons |

### रिटर्न वैल्यू

[Index](../../system/index/) पाए गए तत्व का, या यदि नहीं मिला तो insertion point का बिटवाइज़ कॉम्प्लीमेंट

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const TComparable\&) फ़ंक्शन

परिवर्तनीय सॉर्टेड स्पैन पर बाइनरी खोज करता है।

```cpp
template<typename T,typename TComparable> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const TComparable &comparable)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | The type of elements in the span |
| TComparable | The type of the comparable value |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The sorted span to search |
| comparable | const TComparable\& | The value to search for |

### रिटर्न वैल्यू

[Index](../../system/index/) पाए गए तत्व का, या यदि नहीं मिला तो insertion point का बिटवाइज़ कॉम्प्लीमेंट

## System::MemoryExtensions::BinarySearch(const Span\<T\>\&, const T\&, const SharedPtr\<TComparer\>\&) फ़ंक्शन

कस्टम कंपेयर का उपयोग करके परिवर्तनीय सॉर्टेड स्पैन पर बाइनरी खोज करता है।

```cpp
template<typename T,typename TComparer> int32_t System::MemoryExtensions::BinarySearch(const Span<T> &span, const T &value, const SharedPtr<TComparer> &comparer)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | The type of elements in the span |
| TComparer | The type of the comparer |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The sorted span to search |
| value | const T\& | The value to search for |
| comparer | const [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | The comparer to use for comparisons |

### रिटर्न वैल्यू

[Index](../../system/index/) पाए गए तत्व का, या यदि नहीं मिला तो insertion point का बिटवाइज़ कॉम्प्लीमेंट

## देखें

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)