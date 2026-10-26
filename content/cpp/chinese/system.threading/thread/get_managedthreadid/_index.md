---
title: get_ManagedThreadId()
second_title: Aspose.Slides C++ API 参考
description: 获取线程的标识符。可以从操作系统获取，但如果操作系统线程标识符超出 int 限制，线程的 ID 可能会冲突。
type: docs
weight: 144
url: /zh/system.threading/thread/get_managedthreadid/
---
## Thread::get_ManagedThreadId() const 方法

获取线程的标识符。可以从操作系统获取，但如果操作系统线程标识符超出 int 的限制，线程的 ID 可能会相互冲突。

```cpp
int System::Threading::Thread::get_ManagedThreadId() const
```

### 返回值

伪唯一的线程标识符。

## 另请参见

* 类 [Thread](../)
* 命名空间 [System::Threading](../../)
* 库 [Aspose.Slides](../../../)