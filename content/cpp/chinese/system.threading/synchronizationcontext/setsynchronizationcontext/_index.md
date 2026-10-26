---
title: SetSynchronizationContext()
second_title: Aspose.Slides for C++ API 参考
description: 为当前线程设置同步上下文。
type: docs
weight: 53
url: /zh/system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext(const SharedPtr\<SynchronizationContext\>\&) 方法

为当前线程设置同步上下文。

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| syncContext | const [SharedPtr](../../../system/sharedptr/)\<[SynchronizationContext](../)\>\& | 要为当前线程设置的同步上下文。 |

## 备注

传入 nullptr 将清除当前线程的同步上下文。

## 另见

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [SynchronizationContext](../)
* 命名空间 [System::Threading](../../)
* 库 [Aspose.Slides](../../../)