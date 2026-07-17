---
title: get_CanBeCanceled()
second_title: Aspose.Slides for C++ API 参考
description: 获取此令牌是否能够处于已取消状态。
type: docs
weight: 27
url: /zh/system.threading/cancellationtoken/get_canbecanceled/
---
## CancellationToken::get_CanBeCanceled() const 方法


获取此令牌是否能够处于已取消状态。

```cpp
bool System::Threading::CancellationToken::get_CanBeCanceled() const
```


### 返回值

如果此令牌能够处于已取消状态则返回 true；否则返回 false。
## 备注



由 [CancellationTokenSource](../../cancellationtokensource/) 创建的令牌将返回 true，而 None 令牌始终返回 false。 

## 另见

* 类 [CancellationToken](../)
* 命名空间 [System::Threading](../../)
* 库 [Aspose.Slides](../../../)