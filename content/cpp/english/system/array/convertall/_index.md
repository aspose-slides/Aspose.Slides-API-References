---
title: ConvertAll()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new Array object and fills it with elements of the specified array converted to OutputType type using the specified converter delegate.
type: docs
weight: 599
url: /system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) method


Constructs a new [Array](../) object and fills it with elements of the specified array converted to **OutputType** type using the specified converter delegate.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| InputType | The type of elements of input array |
| OutputType | The type of elements of the resulting array |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | An [Array](../) object |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | A Converter object used to convert each element of the input array to equivalent values of **OutputType** type |

### Return Value

A new array containing values of **OutputType** type equivalent to the values of **input_array**

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) method


Constructs a new [Array](../) object and fills it with elements of the specified array converted to **OutputType** type using the specified converter function object.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| InputType | The type of elements of input array |
| OutputType | The type of elements of the resulting array |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | An [Array](../) object |
| converter | std::function\<OutputType(InputType)> | A function object used to convert each element of the input array to equivalent values of **OutputType** type |

### Return Value

A new array containing values of **OutputType** type equivalent to the values of **input_array**

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)