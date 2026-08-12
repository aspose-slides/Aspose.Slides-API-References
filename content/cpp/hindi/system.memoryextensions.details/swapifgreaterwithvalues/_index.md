---
title: SwapIfGreaterWithValues()
second_title: Aspose.Slides for C++ API संदर्भ
description: यदि तुलना शर्त पूरी होती है तो कुंजी-मान जोड़े बदल देता है।
type: docs
weight: 53
url: /hi/system.memoryextensions.details/swapifgreaterwithvalues/
---
## System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>, int32_t, int32_t) फ़ंक्शन


यदि तुलना शर्त पूरी होती है तो कुंजी-मान जोड़े बदल दिया जाता है।

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer, int32_t i, int32_t j)
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TKey | कुंजियों का प्रकार |
| TValue | मानों का प्रकार |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | कुंजियों का स्पैन |
| values | [Span](../../system/span/)\<TValue\>\& | मानों का स्पैन |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) कुंजियों के लिए फ़ंक्शन |
| i | **int32_t** | तुलना के लिए पहला सूचकांक |
| j | **int32_t** | तुलना के लिए दूसरा सूचकांक |

## संबंधित देखें

* क्लास [Span](../../system/span/)
* नामस्थान [System::MemoryExtensions::Details](../)
* लाइब्रेरी [Aspose.Slides](../../)