---
title: begin()
second_title: Aspose.Slides for C++ API 参考
description: 底层集合的 begin() 方法的访问器。仅当 SmartPtr_ 为具有 begin() 方法的特化类型时才会编译。
type: docs
weight: 378
url: /zh/system/smartptr/begin/
---
## SmartPtr::begin() 方法


对 [begin()](./) 方法的访问器，用于底层集合。仅当 SmartPtr_ 为具有 [begin()](./) 方法的特化类型时才会编译。

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() -> decltype(std::declval<Q>().begin())
```


### 返回值

集合起始位置的迭代器

## SmartPtr::begin() const 方法


对 [begin()](./) 方法的访问器，用于底层集合。仅当 SmartPtr_ 为具有 [begin()](./) 方法的特化类型时才会编译。

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() const -> decltype(std::declval<const Q>().begin())
```


### 返回值

集合起始位置的迭代器

## 参见

* 类 [SmartPtr](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)