---
title: CreateLinkedTokenSource()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個連結的權杖來源，當任何提供的權杖被取消時即會取消。
type: docs
weight: 66
url: /zh-hant/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken\&, const CancellationToken\&) 方法


Creates a linked token source that cancels when any of the provided tokens cancel.

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```


### Arguments

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | 第一個要監控的取消權杖。 |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | 第二個要監控的取消權杖。 |

### 返回值

當任一輸入權杖被取消時，新的權杖來源將會被取消。

## 備註

如果任一輸入權杖已經被取消，返回的來源會立即取消。 

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [CancellationTokenSource](../)
* 類別 [CancellationToken](../../cancellationtoken/)
* 命名空間 [System::Threading](../../)
* 函式庫 [Aspose.Slides](../../../)