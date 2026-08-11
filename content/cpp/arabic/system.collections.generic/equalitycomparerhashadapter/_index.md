---
title: EqualityComparerHashAdapter
second_title: مرجع API لـ Aspose.Slides للغة C++
description: محول لاستخدام IEqualityComparer لعملية التجزئة. يستخدم كائن المقارن، إذا تم تعيينه؛ وإلا، يستخدم طريقة التجزئة المتاحة المختارة باستخدام بنية DictionaryHashSelector.
type: docs
weight: 677
url: /ar/system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter struct

محول لاستخدام [IEqualityComparer](../iequalitycomparer/) لعملية التجزئة. يستخدم كائن المقارن، إذا تم تعيينه؛ وإلا، يستخدم طريقة التجزئة المتاحة المختارة باستخدام بنية [DictionaryHashSelector](../dictionaryhashselector/).

```cpp
template<typename T>class EqualityComparerHashAdapter
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| Hashed | نوع. |

## طرق

| الطريقة | الوصف |
| --- | --- |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | ينشئ محولًا بدون مقارن للاستخدام. |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | ينشئ محولًا بالمقارن المحدد للاستخدام. |
| std::size_t [operator()](./operator_call/)(const T\&) const | يحسب قيمة التجزئة. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | يضبط المقارن للاستخدام. |

## انظر أيضًا

* النطاق [System::Collections::Generic](../)
* المكتبة [Aspose.Slides](../../)