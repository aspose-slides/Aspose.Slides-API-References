---
title: MakeArray()
second_title: Aspose.Slides for C++ API 参考
description: 一个工厂函数，用于构造一个新的 Array 对象，将其填充为指定初始化列表中的元素，并返回指向该 Array 对象的智能指针。
type: docs
weight: 2003
url: /zh/system/makearray/
---
## System::MakeArray(std::initializer_list\<T\>) 函数


一个工厂函数，用于构造一个新的 [Array](../array/) 对象，将其填充为指定初始化列表中的元素，并返回指向 [Array](../array/) 对象的智能指针。

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```


### 模板参数

| Parameter | Description |
| --- | --- |
| T | 函数构造的 [Array](../array/) 对象的元素类型 |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| init | std::initializer_list\<T\> | 包含用于填充数组的元素的初始化列表 |

### 返回值

指向已构造的 [Array](../array/) 对象的智能指针

## System::MakeArray(Args\&&...) 函数


一个工厂函数，用于构造一个新的 [Array](../array/) 对象，并将指定的参数传递给其构造函数。

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```


### 模板参数

| Parameter | Description |
| --- | --- |
| T | 函数构造的 [Array](../array/) 对象的元素类型 |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| args | Args\&&... | 传递给正在构造的 [Array](../array/) 对象的构造函数的参数 |

### 返回值

指向已构造的 [Array](../array/) 对象的智能指针

## System::MakeArray(Integral, Args\&&...) 函数


一个工厂函数，用于构造一个新的 [Array](../array/) 对象，并将指定的参数传递给其构造函数。

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```


### 模板参数

| Parameter | Description |
| --- | --- |
| T | 函数构造的 [Array](../array/) 对象的元素类型 |
| Integral | 数组大小的类型。 |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| size | Integral | 正在创建的数组的大小。 |
| args | Args\&&... | 传递给正在构造的 [Array](../array/) 对象的构造函数的参数 |

### 返回值

指向已构造的 [Array](../array/) 对象的智能指针

## 参见

* Typedef [ArrayPtr](../arrayptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)