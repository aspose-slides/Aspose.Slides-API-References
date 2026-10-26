---
title: Register()
second_title: Aspose.Slides for C++ API 参考
description: 在请求取消时将被调用的回调函数。
type: docs
weight: 40
url: /zh/system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const 方法

Registers a callback that will be invoked when cancellation is requested.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | 当请求取消时要执行的 Action<>。 |

### 返回值

一个可用于注销回调的 [CancellationTokenRegistration](../../cancellationtokenregistration/) 对象。

## 备注

如果取消已经被请求，回调将立即被调用。

回调应该是短暂且非阻塞的，因为它将在调用 [CancellationTokenSource](../../cancellationtokensource/) 上的 Cancel() 的线程上执行。

## 另见

* 类型定义 [Action](../../../system/action/)
* 类 [CancellationTokenRegistration](../../cancellationtokenregistration/)
* 类 [CancellationToken](../)
* 命名空间 [System::Threading](../../)
* 库 [Aspose.Slides](../../../)