---
title: CancellationToken
second_title: Aspose.Slides for C++ API 参考
description: 传播操作应当被取消的通知。此类提供了一种在线程之间进行协作取消的机制，允许一个线程通知其他线程某个操作应当被取消。
type: docs
weight: 14
url: /zh/system.threading/cancellationtoken/
---
## CancellationToken 类

传播操作应当被取消的通知。此类提供了一种在线程之间进行协作取消的机制，允许一个线程通知其他线程某个操作应当被取消。

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## 方法

| 方法 | 描述 |
| --- | --- |
|  [CancellationToken](./cancellationtoken/)() | 默认构造函数。 |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | 获取此令牌是否能够处于已取消状态。 |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | 获取此令牌是否已请求取消。 |
| static [CancellationToken](./) [get_None](./get_none/)() | 返回一个空的 [System::Threading::CancellationToken](./) 值。 |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | 注册一个回调，当请求取消时将被调用。 |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | 如果已请求取消，则抛出 OperationCanceledException。 |

## 备注

[CancellationToken](./) 只能通过其关联的 [CancellationTokenSource](../cancellationtokensource/) 进行取消。

## 另见

* 命名空间 [System::Threading](../)
* 库 [Aspose.Slides](../../)