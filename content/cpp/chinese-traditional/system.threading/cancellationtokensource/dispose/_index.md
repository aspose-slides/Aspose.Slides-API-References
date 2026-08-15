---
title: Dispose()
second_title: Aspose.Slides for C++ API 參考文件
description: 釋放 CancellationTokenSource 所使用的所有資源。
type: docs
weight: 53
url: /zh-hant/system.threading/cancellationtokensource/dispose/
---
## CancellationTokenSource::Dispose() 方法

釋放 [CancellationTokenSource](../) 所使用的所有資源。

```cpp
void System::Threading::CancellationTokenSource::Dispose() override
```

## 備註

取消註冊所有回呼，並使 token 無法使用。  
多次呼叫是安全的，且不會產生其他影響。  

## 另請參閱

* 類別 [CancellationTokenSource](../)
* 命名空間 [System::Threading](../../)
* 函式庫 [Aspose.Slides](../../../)