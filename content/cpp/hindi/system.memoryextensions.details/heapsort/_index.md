---
title: HeapSort()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: की-वैल्यू जोड़ों पर हीप सॉर्ट करता है।
type: docs
weight: 79
url: /hi/system.memoryextensions.details/heapsort/
---
## System::MemoryExtensions::Details::HeapSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) फ़ंक्शन

की-वैल्यू जोड़ों पर हीप सॉर्ट करता है।

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::HeapSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### टेम्प्लेट पैरामीटर

| Parameter | Description |
| --- | --- |
| TKey | कीज़ का प्रकार |
| TValue | वैल्यूज़ का प्रकार |

### आर्गुमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | सॉर्ट करने के लिए keys का स्पैन |
| values | [Span](../../system/span/)\<TValue\>\& | सॉर्ट करने के लिए values का स्पैन |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) keys के लिए फ़ंक्शन |

## देखें

* क्लास [Span](../../system/span/)
* नेमस्पेस [System::MemoryExtensions::Details](../)
* लाइब्रेरी [Aspose.Slides](../../)