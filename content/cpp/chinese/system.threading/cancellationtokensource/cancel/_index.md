---
title: Cancel()
second_title: Aspose.Slides C++ API 参考
description: 传达取消请求。
type: docs
weight: 40
url: /zh/system.threading/cancellationtokensource/cancel/
---
## CancellationTokenSource::Cancel() 方法

传达取消请求。

```cpp
void System::Threading::CancellationTokenSource::Cancel()
```

## 备注

所有已注册的回调将被调用。

后续对 [get_IsCancellationRequested()](../get_iscancellationrequested/) 的调用将返回 true。

回调将在此调用期间同步执行。

## 另见

* 类 [CancellationTokenSource](../)
* 命名空间 [System::Threading](../../)
* 库 [Aspose.Slides](../../../)