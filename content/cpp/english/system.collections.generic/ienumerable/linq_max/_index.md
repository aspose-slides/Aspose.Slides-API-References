---
title: LINQ_Max()
second_title: Aspose.Slides for C++ API Reference
description: Invokes a transform function on each element of a generic sequence and returns the maximum resulting value.
type: docs
weight: 339
url: /system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) method


Invokes a transform function on each element of a generic sequence and returns the maximum resulting value.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| ResultType | The type of the value returned by selector. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | A transform function to apply to each element. |

### Return Value

The maximum value in the sequence.

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) method




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## See Also

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)