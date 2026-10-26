---
title: CreateLinkedTokenSource()
second_title: Aspose.Slides for C++ API 参考
description: 创建一个链接的令牌源，当任意提供的令牌被取消时，该源也会取消。
type: docs
weight: 66
url: /zh/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken&, const CancellationToken&) 方法

创建一个链接的令牌源，当任意提供的令牌被取消时，该源也会取消。

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | 要监视的第一个取消令牌。 |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | 要监视的第二个取消令牌。 |

### 返回值

当任一输入令牌被取消时，将会取消的新令牌源。

## 备注

如果任一输入令牌已经被取消，返回的源将立即取消。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [CancellationTokenSource](../)
* 类 [CancellationToken](../../cancellationtoken/)
* 命名空间 [System::Threading](../../)
* 库 [Aspose.Slides](../../../)