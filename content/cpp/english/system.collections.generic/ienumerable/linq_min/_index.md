---
title: LINQ_Min()
second_title: Aspose.Slides for C++ API Reference
description: Invokes a transform function on each element of a generic sequence and returns the minimum resulting value.
type: docs
weight: 326
url: /system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) method


Invokes a transform function on each element of a generic sequence and returns the minimum resulting value.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
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

The minimum value in the sequence.

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) method




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## See Also

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)