---
title: LINQ_Average()
second_title: Aspose.Slides for C++ API Reference
description: Computes the average of a sequence of numeric values.
type: docs
weight: 365
url: /system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() method


Computes the average of a sequence of numeric values.

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```


### Return Value

The average of the values in the sequence.

## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) method


Computes the average of a sequence of values that are obtained by invoking a transform function on each element of the input sequence.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
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

The average of the projected values.

## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) method




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## See Also

* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)