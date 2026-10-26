---
title: Heapify()
second_title: Aspose.Slides for C++ API संदर्भ
description: कुंजी-मान जोड़ियों के लिए हीप गुणधर्म बनाए रखता है।
type: docs
weight: 92
url: /hi/system.memoryextensions.details/heapify/
---
## System::MemoryExtensions::Details::Heapify(Span\<TKey\>\&, Span\<TValue\>\&, int32_t, int32_t, std::function\<int32_t(const TKey\&, const TKey\&)>) फ़ंक्शन

कुंजी-मान जोड़ियों के लिए हीप गुणधर्म बनाए रखता है।

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::Heapify(Span<TKey> &keys, Span<TValue> &values, int32_t n, int32_t i, std::function<int32_t(const TKey &, const TKey &)> comparer)
```

### टेम्पलेट पैरामीटर

| Parameter | Description |
| --- | --- |
| TKey | कुंजियों का प्रकार |
| TValue | मानों का प्रकार |

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | हीप में कुंजियों का स्पैन |
| values | [Span](../../system/span/)\<TValue\>\& | हीप में मानों का स्पैन |
| n | **int32_t** | हीप का आकार |
| i | **int32_t** | [Index](../../system/index/) से हीपिफ़ाइ करने के लिए |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) कियों के लिए फ़ंक्शन |

## संबंधित देखें

* क्लास [Span](../../system/span/)
* नेमस्पेस [System::MemoryExtensions::Details](../)
* लाइब्रेरी [Aspose.Slides](../../)