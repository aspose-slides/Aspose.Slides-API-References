---
title: PickPivotAndPartition()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: क्विकसॉर्ट के लिए पिवट का चयन करता है और कुंजी-मान जोड़ों को विभाजित करता है।
type: docs
weight: 105
url: /hi/system.memoryextensions.details/pickpivotandpartition/
---
## System::MemoryExtensions::Details::PickPivotAndPartition(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>) फ़ंक्शन

किवर्ट के लिए पिवट का चयन करता है और क्विकसॉर्ट हेतु कुंजी-मान जोड़ों को विभाजित करता है।

```cpp
template<typename TKey,typename TValue> int32_t System::MemoryExtensions::Details::PickPivotAndPartition(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TKey | कियों का प्रकार |
| TValue | मानों का प्रकार |

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | विभाजन के लिए कियों का स्पैन |
| values | [Span](../../system/span/)\<TValue\>\& | विभाजन के लिए मानों का स्पैन |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) कियों के लिए फ़ंक्शन |

### रिटर्न वैल्यू

विभाजन के बाद पिवट इंडेक्स

## संबंधित देखें

* क्लास [Span](../../system/span/)
* नेमस्पेस [System::MemoryExtensions::Details](../)
* लाइब्रेरी [Aspose.Slides](../../)