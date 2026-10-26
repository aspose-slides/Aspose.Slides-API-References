---
title: ConvertAll()
second_title: Aspose.Slides C++ API 参考
description: 构造一个新的 Array 对象，并使用指定的转换器委托将指定数组的元素转换为 OutputType 类型后填充该对象。
type: docs
weight: 625
url: /zh/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) method

构造一个新的 [Array](../) 对象，并使用指定的转换器委托将指定数组的元素转换为 **OutputType** 类型后填充该对象。

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| InputType | 输入数组的元素类型 |
| OutputType | 结果数组的元素类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | 一个 [Array](../) 对象 |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | 用于将输入数组的每个元素转换为等价的 **OutputType** 类型值的 Converter 对象 |

### 返回值

返回一个新数组，其中包含等价于 **input_array** 中值的 **OutputType** 类型的值。

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) method

构造一个新的 [Array](../) 对象，并使用指定的转换函数对象将指定数组的元素转换为 **OutputType** 类型后填充该对象。

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| InputType | 输入数组的元素类型 |
| OutputType | 结果数组的元素类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | 一个 [Array](../) 对象 |
| converter | std::function\<OutputType(InputType)> | 用于将输入数组的每个元素转换为等价的 **OutputType** 类型值的函数对象 |

### 返回值

返回一个新数组，其中包含等价于 **input_array** 中值的 **OutputType** 类型的值。

## 另请参阅

* 类型定义 [ArrayPtr](../../arrayptr/)
* 类型定义 [Converter](../../converter/)
* 类 [Array](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)