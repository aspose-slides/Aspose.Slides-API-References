---
title: operator()()
second_title: Aspose.Slides for C++ API 参考
description: 比较实现 IComparable 接口的值类型。
type: docs
weight: 1
url: /zh/system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q\&, const Q\&) const 方法

比较实现 [IComparable](../../../system/icomparable/) 接口的值类型。

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Q | 要比较的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | const Q\& | 左侧值。 |
| b | const Q\& | 右侧值。 |

### 返回值

如果 **a** 被认为小于 **b**，则返回 True，否则返回 false。

## ComparerType::operator()(const Q\&, const Q\&) const 方法

比较原始值类型以及未实现 [IComparable](../../../system/icomparable/) 接口的对象。

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Q | 要比较的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | const Q\& | 左侧值。 |
| b | const Q\& | 右侧值。 |

### 返回值

如果 **a** 被认为小于 **b**，则返回 True，否则返回 false。

## ComparerType::operator()(const Q\&, const Q\&) const 方法

比较浮点类型。

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Q | 要比较的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | const Q\& | 左侧值。 |
| b | const Q\& | 右侧值。 |

### 返回值

如果 **a** 被认为小于 **b**，则返回 True，否则返回 false。

## 另请参阅

* 类 [IComparable](../../../system/icomparable/)
* 结构体 [has_method_compareto](../../has_method_compareto/)
* 结构体 [ComparerType](../)
* 命名空间 [System::Collections::Generic::Details](../../)
* 库 [Aspose.Slides](../../../)