---
title: get_Current()
second_title: Aspose.Slides for C++ API 参考
description: 获取当前线程的同步上下文。
type: docs
weight: 40
url: /zh/system.threading/synchronizationcontext/get_current/
---
## SynchronizationContext::get_Current() 方法

获取当前线程的同步上下文。

```cpp
static const SharedPtr<SynchronizationContext> & System::Threading::SynchronizationContext::get_Current()
```

### 返回值

SharedPtr<SynchronizationContext> 指向当前线程的同步上下文的共享指针。

## 备注

如果当前线程未设置同步上下文，则返回 null。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [SynchronizationContext](../)
* 命名空间 [System::Threading](../../)
* Library [Aspose.Slides](../../../)