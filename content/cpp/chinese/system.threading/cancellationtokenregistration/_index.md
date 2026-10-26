---
title: CancellationTokenRegistration
second_title: Aspose.Slides for C++ API 参考
description: 表示对取消令牌回调的注册。
type: docs
weight: 27
url: /zh/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration 类

表示对取消令牌回调的注册。

```cpp
class CancellationTokenRegistration
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [Dispose](./dispose/)() | 释放该注册并从关联的 [CancellationTokenSource](../cancellationtokensource/) 中移除回调。调用此方法后，当关联的 [CancellationTokenSource](../cancellationtokensource/) 被取消时，已注册的回调将不再被调用。 |

## 备注

此类允许从取消令牌中注销回调。释放时，它会从关联的 [CancellationTokenSource](../cancellationtokensource/) 中移除回调。  
此类不应直接创建——它由 [CancellationToken](../cancellationtoken/) 注册方法返回。

## 另见

* 命名空间 [System::Threading](../)
* 库 [Aspose.Slides](../../)