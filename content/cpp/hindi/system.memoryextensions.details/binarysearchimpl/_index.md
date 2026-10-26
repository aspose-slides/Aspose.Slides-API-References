---
title: BinarySearchImpl()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: सामान्य बाइनरी खोज कार्यान्वयन।
type: docs
weight: 118
url: /hi/system.memoryextensions.details/binarysearchimpl/
---
## System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan\<T\>\&, const TValue\&, TCompareFunc) फ़ंक्शन

सामान्य बाइनरी खोज कार्यान्वयन।

```cpp
template<typename T,typename TValue,typename TCompareFunc> int32_t System::MemoryExtensions::Details::BinarySearchImpl(const ReadOnlySpan<T> &span, const TValue &value, TCompareFunc compareFunc)
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |
| TValue | खोजे जाने वाले मान का प्रकार |
| TCompareFunc | तुलना के लिए फ़ंक्शन प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | खोजने के लिए स्पैन |
| value | const TValue\& | खोजे जाने वाला मान |
| compareFunc | TCompareFunc | फ़ंक्शन जो मान की तुलना स्पैन तत्व से करता है और **int32_t** (-1, 0, 1) लौटाता है |

### वापसी मान

[Index](../../system/index/) पाया गया तत्व या सम्मिलन बिंदु का बिटवाइज़ पूरक

## संबंधित देखें

* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* नेमस्पेस [System::MemoryExtensions::Details](../)
* लाइब्रेरी [Aspose.Slides](../../)