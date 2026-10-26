---
title: InsertionSort()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: की-वैल्यू जोड़ों पर इंसर्शन सॉर्ट करता है।
type: docs
weight: 66
url: /hi/system.memoryextensions.details/insertionsort/
---
## System::MemoryExtensions::Details::InsertionSort(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) फ़ंक्शन

की-वैल्यू जोड़ों पर इंसर्शन सॉर्ट करता है।

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::InsertionSort(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TKey | कियों का प्रकार |
| TValue | वैल्यूज़ का प्रकार |

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | सॉर्ट करने के लिए कियों का स्पैन |
| values | [Span](../../system/span/)\<TValue\>\& | सॉर्ट करने के लिए वैल्यूज़ का स्पैन |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) कुंजी के लिए फ़ंक्शन |

## संबंधित देखें

* क्लास [Span](../../system/span/)
* नेमस्पेस [System::MemoryExtensions::Details](../)
* लाइब्रेरी [Aspose.Slides](../../)