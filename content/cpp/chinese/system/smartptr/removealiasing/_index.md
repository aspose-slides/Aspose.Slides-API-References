---
title: RemoveAliasing()
second_title: Aspose.Slides C++ API 参考
description: 从指针中移除别名（由别名构造函数创建），并确保它管理（如果是共享的）或跟踪（如果是弱引用的）它所指向的相同对象。
type: docs
weight: 170
url: /zh/system/smartptr/removealiasing/
---
## SmartPtr::RemoveAliasing() const 方法

从指针中移除别名（由别名构造函数创建），并确保它管理（如果是共享的）或跟踪（如果是弱引用的）它所指向的相同对象。

```cpp
SmartPtr_ System::SmartPtr<T>::RemoveAliasing() const
```

### 返回值

指向此指针所指向的相同对象的指针，并负责该对象的生命周期。

## 另见

* Typedef [SmartPtr_](../smartptr_/)
* 类 [SmartPtr](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)