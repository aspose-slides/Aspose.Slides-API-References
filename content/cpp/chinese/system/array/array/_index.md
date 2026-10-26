---
title: Array()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个空数组。
type: docs
weight: 1
url: /zh/system/array/array/
---
## Array::Array() 构造函数

构造一个空数组。

```cpp
System::Array<T>::Array()
```

## Array::Array(int, const T\&) 构造函数

填充构造函数。

```cpp
System::Array<T>::Array(int count, const T &init=T())
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| count | int | 数组的初始大小 |
| init | const T\& | 用于填充数组的初始值 |

## Array::Array(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<ValueType\>::value\&&std::is_convertible\<ValueType, T\>::value, int\>::type, ValueType) 构造函数

填充构造函数。

```cpp
template<typename ValueType> System::Array<T>::Array(typename std::enable_if<std::is_arithmetic<T>::value &&std::is_arithmetic<ValueType>::value &&std::is_convertible<ValueType, T>::value, int>::type count, ValueType init)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| ValueType | 初始值的类型 |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| count | typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](../valuetype/)\>::value\&&std::is_convertible\<[ValueType](../valuetype/), T\>::value, int\>::type | 数组的初始大小 |
| init | [ValueType](../valuetype/) | 用于填充数组的初始值 |

## Array::Array(int, const T) 构造函数

填充构造函数。

```cpp
System::Array<T>::Array(int count, const T inits[])
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| count | int | 数组的初始大小 |
| inits | const T | 用于填充数组的值 |

## Array::Array(vector_t\&&) 构造函数

移动构造函数。

```cpp
System::Array<T>::Array(vector_t &&value)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| value | **vector_t**\&& | std::vector，数组获取其元素 |

## Array::Array(const vector_t\&) 构造函数

拷贝构造函数。

```cpp
System::Array<T>::Array(const vector_t &assgn)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| assgn | const **vector_t**\& | 要从中复制值的 std::vector |

## Array::Array(const std::vector\<Q\>\&) 构造函数

构造一个[Array](../)对象，并使用从 std::vector 对象复制的值进行填充，该对象的值类型与 **T** 相同但不同于 **UnderlyingType**。

```cpp
template<typename Q,typename> System::Array<T>::Array(const std::vector<Q> &value)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| Q | 要从中复制元素的 std::vector 对象的元素类型 |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const std::vector\<Q\>\& | 要从中复制值的 std::vector |

## Array::Array(std::vector\<Q\>\&&) 构造函数

构造一个[Array](../)对象，并使用从 std::vector 对象移动的值进行填充，该对象的值类型与 **T** 相同但不同于 **UnderlyingType**。

```cpp
template<typename Q,typename> System::Array<T>::Array(std::vector<Q> &&value)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| Q | 要从中移动元素的 std::vector 对象的元素类型 |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| value | std::vector\<Q\>\&& | 要从中复制值的 std::vector |

## Array::Array(std::initializer_list\<UnderlyingType\>) 构造函数

构造一个[Array](../)对象，并使用包含 **UnderlyingType** 类型元素的指定初始化列表中的值进行填充。

```cpp
System::Array<T>::Array(std::initializer_list<UnderlyingType> init)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| init | std::initializer_list\<[UnderlyingType](../underlyingtype/)\> | 包含用于填充数组的元素的初始化列表 |

## Array::Array(const std::array\<UnderlyingType, InitArraySize\>\&) 构造函数

构造一个[Array](../)对象，并使用包含 **UnderlyingType** 类型元素的指定数组中的值进行填充。

```cpp
template<std::size_t> System::Array<T>::Array(const std::array<UnderlyingType, InitArraySize> &init)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| InitArraySize | **init** 数组的元素数量。 |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| init | const std::array\<[UnderlyingType](../underlyingtype/), InitArraySize\>\& | [Array](../) 用于复制到正在构建的数组中。 |

## Array::Array(std::initializer_list\<bool\>, int) 构造函数

构造一个[Array](../)对象，并使用包含 bool 类型元素的指定初始化列表中的值进行填充。

```cpp
System::Array<T>::Array(std::initializer_list<bool> init, int=0)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| init | std::initializer_list\<**bool**\> | 包含用于填充数组的元素的初始化列表 |

## 另请参见

* 类型定义 [ValueType](../valuetype/)
* 类型定义 [UnderlyingType](../underlyingtype/)
* 类 [Array](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)