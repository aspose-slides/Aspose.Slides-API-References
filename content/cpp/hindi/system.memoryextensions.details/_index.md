---
title: "System::MemoryExtensions::Details"
second_title: "Aspose.Slides for C++ API संदर्भ"
description: 
type: docs
weight: 638
url: /hi/system.memoryextensions.details/
---
## फ़ंक्शन

| फ़ंक्शन | विवरण |
| --- | --- |
| **int32_t** [Compare](./compare/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<U\>\&) | दो स्मार्ट पॉइंटर्स की तुलना करता है। |
| **int32_t** [Compare](./compare/)(const T\&, const T\&) | दो अंकात्मक मानों की तुलना करता है। |
| **int32_t** [Compare](./compare/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, const U\&) | स्मार्ट पॉइंटर की एक मान के साथ तुलना करता है। |
| **int32_t** [LastIndexOfImpl](./lastindexofimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**, const T\&) | स्पैन में एक मान का अंतिम इंडेक्स ढूँढ़ता है। |
| **bool** [SequenceEqualImpl](./sequenceequalimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const **int32_t**, **int32_t**, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | निर्दिष्ट स्थितियों से शुरू होकर दो स्पैन समान हैं या नहीं जाँचता है। |
| void [IntroSort](./introsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, **int32_t**, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | की-वैल्यू जोड़ों के लिए इंट्रॉसोर्ट एल्गोरिद्म का आंतरिक कार्यान्वयन। |
| void [SwapIfGreaterWithValues](./swapifgreaterwithvalues/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>, **int32_t**, **int32_t**) | अगर तुलना शर्त पूरी होती है तो की-वैल्यू जोड़ों का अदला-बदली करता है। |
| void [InsertionSort](./insertionsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | की-वैल्यू जोड़ों पर इन्सर्शन सॉर्ट करता है। |
| void [HeapSort](./heapsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | की-वैल्यू जोड़ों पर हीप सॉर्ट करता है। |
| void [Heapify](./heapify/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, **int32_t**, **int32_t**, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | की-वैल्यू जोड़ों के लिए हीप प्रॉपर्टी को बनाए रखता है। |
| **int32_t** [PickPivotAndPartition](./pickpivotandpartition/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | क्विकसॉर्ट के लिए पिवट चुनता है और की-वैल्यू जोड़ों को विभाजित करता है। |
| **int32_t** [BinarySearchImpl](./binarysearchimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const TValue\&, TCompareFunc) | सामान्य बाइनरी सर्च कार्यान्वयन। |