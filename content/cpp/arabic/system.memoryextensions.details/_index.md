---
title: "System::MemoryExtensions::Details"
second_title: مرجع Aspose.Slides للغة C++
description: 
type: docs
weight: 638
url: /ar/system.memoryextensions.details/
---
## الدوال

| الدالة | الوصف |
| --- | --- |
| **int32_t** [Compare](./compare/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<U\>\&) | يقارن مؤشرين ذكيين. |
| **int32_t** [Compare](./compare/)(const T\&, const T\&) | يقارن قيمتين حسابيتين. |
| **int32_t** [Compare](./compare/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, const U\&) | يقارن مؤشرًا ذكياً بقيمة. |
| **int32_t** [LastIndexOfImpl](./lastindexofimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**, const T\&) | يجد الفهرس الأخير لقيمة في نطاق. |
| **bool** [SequenceEqualImpl](./sequenceequalimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const **int32_t**, **int32_t**, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | يتحقق مما إذا كان نطاقان متساويان بدءًا من مواضع محددة. |
| void [IntroSort](./introsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, **int32_t**, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | تنفيذ داخلي لخوارزمية introsort للأزواج المفتاح-القيمة. |
| void [SwapIfGreaterWithValues](./swapifgreaterwithvalues/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>, **int32_t**, **int32_t**) | يبدل أزواج المفتاح-القيمة إذا تم استيفاء شرط المقارنة. |
| void [InsertionSort](./insertionsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | يُجري فرز الإدراج على أزواج المفتاح-القيمة. |
| void [HeapSort](./heapsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | يُجري فرز الكومة على أزواج المفتاح-القيمة. |
| void [Heapify](./heapify/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, **int32_t**, **int32_t**, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | يحافظ على خاصية الكومة لأزواج المفتاح-القيمة. |
| **int32_t** [PickPivotAndPartition](./pickpivotandpartition/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | يختار محورًا ويقسم أزواج المفتاح-القيمة للفرز السريع. |
| **int32_t** [BinarySearchImpl](./binarysearchimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const TValue\&, TCompareFunc) | تنفيذ شائع للبحث الثنائي. |