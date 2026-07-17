---
title: cend()
second_title: Aspose.Slides C++ API 参考
description: 底层集合的 cend() 方法的访问器。仅在 SmartPtr_ 为具有 cend() 方法的特化类型时编译。
type: docs
weight: 417
url: /zh/system/smartptr/cend/
---
## SmartPtr::cend() const 方法


访问底层集合的 [cend()](./) 方法。如果 SmartPtr_ 是具有 [cend()](./) 方法的特化类型，则仅在此情况下编译。

```cpp
template<typename Q> auto System::SmartPtr<T>::cend() const -> decltype(std::declval<const Q>().cend())
```


### 返回值

迭代器指向集合的结束位置

## 另见

* 类 [SmartPtr](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)