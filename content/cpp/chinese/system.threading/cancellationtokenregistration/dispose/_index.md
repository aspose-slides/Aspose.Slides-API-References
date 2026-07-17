---
title: Dispose()
second_title: Aspose.Slides for C++ API 参考
description: 释放注册并从关联的 CancellationTokenSource 中移除回调。调用此方法后，当关联的 CancellationTokenSource 被取消时，已注册的回调将不再被调用。
type: docs
weight: 1
url: /zh/system.threading/cancellationtokenregistration/dispose/
---
## CancellationTokenRegistration::Dispose() 方法


释放注册并从关联的 [CancellationTokenSource](../../cancellationtokensource/) 中移除回调。调用此方法后，当关联的 [CancellationTokenSource](../../cancellationtokensource/) 被取消时，已注册的回调将不再被调用。

```cpp
void System::Threading::CancellationTokenRegistration::Dispose()
```

## 备注



安全地多次调用此方法——后续调用不会产生任何效果。 

## 另请参阅

* 类 [CancellationTokenRegistration](../)
* 命名空间 [System::Threading](../../)
* 库 [Aspose.Slides](../../../)