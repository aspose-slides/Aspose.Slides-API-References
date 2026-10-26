---
title: Equals()
second_title: Aspose.Slides for C++ API 参考
description: 使用 operator==() 确定指定值的相等性。
type: docs
weight: 66
url: /zh/system.boxedvaluedetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) 函数

使用 [operator==()](../../system/operator_equal_equal/) 确定指定值的相等性。

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| The | type of the values being compared |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| value1 | T | The first comparand |
| value2 | T | The second comparand |

### 返回值

True if the specified value are equal as determined by [operator==()](../../system/operator_equal_equal/), otherwise - false

## System::BoxedValueDetail::Equals(T, T) 函数

使用 method [System::Object::Equals()](../../system/object/equals/) 确定指定值的相等性。

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| The | type of the values being compared |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| value1 | T | The first comparand |
| value2 | T | The second comparand |

### 返回值

True if the specified value are equal as determined by method [Equals()](./), otherwise - false

## 另请参见

* 命名空间 [System::BoxedValueDetail](../)
* 库 [Aspose.Slides](../../)