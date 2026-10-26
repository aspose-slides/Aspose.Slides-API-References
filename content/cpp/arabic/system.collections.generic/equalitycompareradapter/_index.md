---
title: EqualityComparerAdapter
second_title: Aspose.Slides لمرجع API للغة C++
description: "محول يجعل من الممكن استخدام IEqualityComparer مع مجموعات وخوارزميات على نمط STL. يستخدم IEqualityComparer إذا تم تعيينه. إذا لم يُحدد، يستخدم operator == أو Object::Equals أو T::Equals، أيهما متاح."
type: docs
weight: 664
url: /ar/system.collections.generic/equalitycompareradapter/
---
## هيكل EqualityComparerAdapter


محول يجعل من الممكن استخدام [IEqualityComparer](../iequalitycomparer/) مع مجموعات وخوارزميات على نمط STL. يستخدم [IEqualityComparer](../iequalitycomparer/) إذا تم تعيينه. إذا لم يتم تعيينه، يستخدم operator ==، [Object::Equals](../../system/object/equals/) أو T::Equals، أيهما متاح.

```cpp
template<class T>class EqualityComparerAdapter
```


### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T | النوع الذي يتم مقارنته. |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | ينشئ محولًا لا يستخدم أي مُقارن. |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | ينشئ محولًا باستخدام المُقارن المعطى. |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | يقارن كائنين. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | يضبط المُقارن. |

## انظر أيضًا

* النطاق [System::Collections::Generic](../)
* المكتبة [Aspose.Slides](../../)