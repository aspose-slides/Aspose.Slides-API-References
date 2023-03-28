---
title: MakeArray()
second_title: Aspose.Slides for C++ API Reference
description: A factory function that constructs a new Array object, fills it with the elements from the specified initialization list and returns a smart pointer pointing to the Array object.
type: docs
weight: 1860
url: /cpp/system/makearray/
---
## System::MakeArray(std::initializer_list\<T\>) function


A factory function that constructs a new [Array](../array/) object, fills it with the elements from the specified initialization list and returns a smart pointer pointing to the [Array](../array/) object.

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements of the [Array](../array/) object the function constructs |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| init | std::initializer_list\<T\> | The initialization list containing the elements to fill the array with |

### Return Value

A smart pointer pointing to the constructed [Array](../array/) object

## See Also

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
## System::MakeArray(Args\&&...) function


A factory function that constructs a new [Array](../array/) object passing the specified arguments to its constructor.

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements of the [Array](../array/) object the function constructs |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| args | Args\&&... | The arguments that are passed to the constructor of the [Array](../array/) object being constructed |

### Return Value

A smart pointer pointing to the constructed [Array](../array/) object

## See Also

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
## System::MakeArray(Integral, Args\&&...) function


A factory function that constructs a new [Array](../array/) object passing the specified arguments to its constructor.

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The type of elements of the [Array](../array/) object the function constructs |
| Integral | Type of array size. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| size | Integral | Size of the array being created. |
| args | Args\&&... | The arguments that are passed to the constructor of the [Array](../array/) object being constructed |

### Return Value

A smart pointer pointing to the constructed [Array](../array/) object

## See Also

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
