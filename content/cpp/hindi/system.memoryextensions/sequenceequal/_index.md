---
title: SequenceEqual()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित करता है कि क्या दो ReadOnlySpans समान क्रम में समान तत्वों को समाहित करते हैं।
type: docs
weight: 326
url: /hi/system.memoryextensions/sequenceequal/
---
## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन

निर्धारित करता है कि क्या दो ReadOnlySpans समान क्रम में समान तत्वों को समाहित करते हैं।

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &first, const ReadOnlySpan<T> &second)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |

### पैरामीटर

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| first | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | तुलना करने के लिए पहला स्पैन |
| second | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | तुलना करने के लिए दूसरा स्पैन |

### रिटर्न वैल्यू

यदि स्पैन्स की लंबाई समान है और सभी तत्व समान हैं तो true, अन्यथा false

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) फ़ंक्शन

निर्धारित करता है कि क्या [Span](../../system/span/) और [ReadOnlySpan](../../system/readonlyspan/) समान क्रम में समान तत्वों को समाहित करते हैं।

```cpp
template<typename T> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |

### पैरामीटर

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | तुलना करने के लिए [Span](../../system/span/) |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | तुलना करने के लिए [ReadOnlySpan](../../system/readonlyspan/) |

### रिटर्न वैल्यू

यदि स्पैन्स की लंबाई समान है और सभी तत्व समान हैं तो true, अन्यथा false

## System::MemoryExtensions::SequenceEqual(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) फ़ंक्शन

निर्धारित करता है कि क्या दो ReadOnlySpans कस्टम तुलनाकर्ता का उपयोग करके समान तत्वों को समाहित करते हैं।

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |
| TComparer | तुलनाकर्ता ऑब्जेक्ट का प्रकार |

### पैरामीटर

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | तुलना करने के लिए पहला स्पैन |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | तुलना करने के लिए दूसरा स्पैन |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | तत्व तुलना के लिए तुलनाकर्ता ऑब्जेक्ट का स्मार्ट पॉइंटर |

### रिटर्न वैल्यू

यदि स्पैन्स की लंबाई समान है और comparer सभी तत्वों को समान मानता है तो true, अन्यथा false

## System::MemoryExtensions::SequenceEqual(const Span\<T\>\&, const ReadOnlySpan\<T\>\&, SharedPtr\<TComparer\>\&) फ़ंक्शन

निर्धारित करता है कि क्या [Span](../../system/span/) और [ReadOnlySpan](../../system/readonlyspan/) कस्टम तुलनाकर्ता का उपयोग करके समान तत्वों को समाहित करते हैं।

```cpp
template<typename T,typename TComparer> bool System::MemoryExtensions::SequenceEqual(const Span<T> &span, const ReadOnlySpan<T> &other, SharedPtr<TComparer> &comparer)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |
| TComparer | तुलनाकर्ता ऑब्जेक्ट का प्रकार |

### पैरामीटर

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | तुलना करने के लिए [Span](../../system/span/) |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | तुलना करने के लिए [ReadOnlySpan](../../system/readonlyspan/) |
| comparer | [SharedPtr](../../system/sharedptr/)\<TComparer\>\& | तत्व तुलना के लिए तुलनाकर्ता ऑब्जेक्ट का स्मार्ट पॉइंटर |

### रिटर्न वैल्यू

यदि स्पैन्स की लंबाई समान है और comparer सभी तत्वों को समान मानता है तो true, अन्यथा false

## देखें भी

* टाइपडिफ [SharedPtr](../../system/sharedptr/)
* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* क्लास [Span](../../system/span/)
* नेमस्पेस [System::MemoryExtensions](../)
* लाइब्रेरी [Aspose.Slides](../../)