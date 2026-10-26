---
title: end()
second_title: Aspose.Slides C++ API 参考
description: 获取底层集合的 end() 方法。仅当 SmartPtr_ 为具有 end() 方法的特化类型时才会编译。
type: docs
weight: 391
url: /zh/system/smartptr/end/
---
## SmartPtr::end() 方法

获取底层集合的 [end()](./) 方法。仅当 SmartPtr_ 为具有 [end()](./) 方法的特化类型时才会编译。

```cpp
template<typename Q> auto System::SmartPtr<T>::end() -> decltype(std::declval<Q>().end())
```

### 返回值

指向集合末尾的迭代器

## SmartPtr::end() const 方法

获取底层集合的 [end()](./) 方法。仅当 SmartPtr_ 为具有 [end()](./) 方法的特化类型时才会编译。

```cpp
template<typename Q> auto System::SmartPtr<T>::end() const -> decltype(std::declval<const Q>().end())
```

### 返回值

指向集合末尾的迭代器

## 另请参阅

* 类 [SmartPtr](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)