---
title: LINQ_SelectMany()
second_title: Aspose.Slides for C++ API Reference
description: Projects each element of a sequence and combines the resulting sequences into one sequence.
type: docs
weight: 261
url: /system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) method


Projects each element of a sequence and combines the resulting sequences into one sequence.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| ResultType | The type of the value returned by the **selector**. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | A transform function. |

### Return Value

An [IEnumerable](../) that contains the result of invoking a one-to-many projection function on each element of the input sequence.

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)