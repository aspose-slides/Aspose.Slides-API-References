---
title: operator()()
second_title: Aspose.Slides for C++ API 参考
description: 适用于实现了 operator < 的类型的比较函数。
type: docs
weight: 27
url: /zh/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q&, const Q&) const 方法


[Comparison](../../../system/comparison/) 适用于实现了 operator < 的类型的函数。

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| Q | 正在比较的类型；用于类型转换可用性的模板。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | const Q& | 第一个要比较的值。 |
| y | const Q& | 第二个要比较的值。 |

### 返回值

如果 **x** 被视为小于 **y**，则返回 true，否则返回 false。

## ComparerAdapter::operator()(const Q&, const Q&) const 方法


[Comparison](../../../system/comparison/) 适用于未实现 operator < 的类型的函数。

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| Q | 正在比较的类型；用于类型转换可用性的模板。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | const Q& | 第一个要比较的值。 |
| y | const Q& | 第二个要比较的值。 |

### 返回值

如果已设置比较器且 **x** 被视为小于 **y**，则返回 true，否则返回 false。

## 另请参见

* 结构体 [ComparerAdapter](../)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)