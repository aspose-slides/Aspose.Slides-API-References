---
title: Cancel()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳遞取消請求。
type: docs
weight: 40
url: /zh-hant/system.threading/cancellationtokensource/cancel/
---
## CancellationTokenSource::Cancel() 方法


傳遞取消請求。

```cpp
void System::Threading::CancellationTokenSource::Cancel()
```

## 備註



所有已註冊的回呼函式將被呼叫。 

後續對 [get_IsCancellationRequested()](../get_iscancellationrequested/) 的呼叫將回傳 true。 

回呼函式在此呼叫期間同步執行。 

## 另請參閱

* 類別 [CancellationTokenSource](../)
* 命名空間 [System::Threading](../../)
* 函式庫 [Aspose.Slides](../../../)