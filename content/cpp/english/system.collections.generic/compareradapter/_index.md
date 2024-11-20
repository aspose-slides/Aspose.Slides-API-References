---
title: ComparerAdapter
second_title: Aspose.Slides for C++ API Reference
description: Adapter to use IComparer within STL environment. Uses IComparer if set; otherwise, uses operator < (if available) or returns false (if not).
type: docs
weight: 638
url: /system.collections.generic/compareradapter/
---
## ComparerAdapter struct


Adapter to use [IComparer](../icomparer/) within STL environment. Uses [IComparer](../icomparer/) if set; otherwise, uses operator < (if available) or returns false (if not).

```cpp
template<class T>class ComparerAdapter
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type being compared. |
## Methods

| Method | Description |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | Constructs adapter without any comparator available. |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Constructs adapter. |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) function for types with operator < available. |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) function for types with operator < not available. |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | Sets comparator object. |

## See Also

* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)