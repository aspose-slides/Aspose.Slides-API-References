---
title: ForEach()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: IEnumerable पर एक foreach ऑपरेशन को निष्पादित करता है जिसमें दोहराव समानांतर रूप से चल सकते हैं।
type: docs
weight: 1
url: /hi/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) विधि

एक IEnumerable पर foreach ऑपरेशन को निष्पादित करता है जिसमें दोहराव समानांतर रूप से चल सकते हैं।

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TSource | स्रोत में डेटा का प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | एक enumerable डेटा स्रोत। |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | एक वस्तु जो इस ऑपरेशन के व्यवहार को कॉन्फ़िगर करती है। |
| body | const [Action](../../../system/action/)\<TSource\>\& | डेलीगेट जो प्रत्येक दोहराव पर एक बार बुलाया जाता है। |

### वापसी मान

एक [ParallelLoopResult](../../parallelloopresult/) संरचना जो लूप के किस हिस्से का पूर्ण होना है, इसकी जानकारी रखती है।

## टिप्पणियाँ

यह विधि स्रोत enumerable को विभाजित करती है और कई थ्रेड्स पर एक साथ बॉडी डेलीगेट को निष्पादित करती है।

## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) विधि

एक IEnumerable पर foreach ऑपरेशन को निष्पादित करता है जिसमें दोहराव समानांतर रूप से चल सकते हैं।

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| TSource | स्रोत में डेटा का प्रकार। |

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | एक enumerable डेटा स्रोत। |
| body | const [Action](../../../system/action/)\<TSource\>\& | डेलीगेट जो प्रत्येक दोहराव पर एक बार बुलाया जाता है। |

### वापसी मान

एक [ParallelLoopResult](../../parallelloopresult/) संरचना जो लूप के किस हिस्से का पूर्ण होना है, इसकी जानकारी रखती है।

## टिप्पणियाँ

असीमित समानांतरता और बिना रद्दीकरण के डिफ़ॉल्ट [ParallelOptions](../../paralleloptions/) का उपयोग करता है।

## संबंधी देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ़ [Action](../../../system/action/)
* क्लास [ParallelLoopResult](../../parallelloopresult/)
* क्लास [IEnumerable](../../../system.collections.generic/ienumerable/)
* क्लास [ParallelOptions](../../paralleloptions/)
* क्लास [Parallel](../)
* नेमस्पेस [System::Threading::Tasks](../../)
* लाइब्रेरी [Aspose.Slides](../../../)