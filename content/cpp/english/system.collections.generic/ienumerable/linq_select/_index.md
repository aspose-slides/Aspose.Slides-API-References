---
title: LINQ_Select()
second_title: Aspose.Slides for C++ API Reference
description: Transforms elements of a sequence.
type: docs
weight: 222
url: /system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) method


Transforms elements of a sequence.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| ResultType | The type of the value returned by the **selector**. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | A transform function. |

### Return Value

An [IEnumerable](../) that contains elements returned by the **selector** function.

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) method


Transforms each element of a sequence into a new form by incorporating the element's index.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| ResultType | The type of the value returned by the **selector**. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | A transform function. |

### Return Value

An [IEnumerable](../) that contains elements returned by the **selector** function.

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)