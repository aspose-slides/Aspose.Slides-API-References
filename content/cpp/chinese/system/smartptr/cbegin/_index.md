---
title: cbegin()
second_title: Aspose.Slides for C++ API 参考
description: 底层集合的 cbegin() 方法的访问器。仅当 SmartPtr_ 为具有 cbegin() 方法的特化类型时才会编译。
type: docs
weight: 404
url: /zh/system/smartptr/cbegin/
---
## SmartPtr::cbegin() const 方法

访问 [cbegin()](./) 方法的底层集合的访问器。仅在 SmartPtr_ 为具有 [cbegin()](./) 方法的特化类型时编译。

```cpp
template<typename Q> auto System::SmartPtr<T>::cbegin() const -> decltype(std::declval<const Q>().cbegin())
```

### 返回值

指向集合起始位置的迭代器

## 另请参阅

* 类 [SmartPtr](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)