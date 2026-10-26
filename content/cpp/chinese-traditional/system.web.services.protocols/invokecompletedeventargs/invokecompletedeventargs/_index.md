---
title: InvokeCompletedEventArgs()
second_title: Aspose.Slides for C++ API 參考
description: 建立新實例。
type: docs
weight: 14
url: /zh-hant/system.web.services.protocols/invokecompletedeventargs/invokecompletedeventargs/
---
## InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) 建構函式


建立新實例。

```cpp
System::Web::Services::Protocols::InvokeCompletedEventArgs::InvokeCompletedEventArgs(Exception error, bool cancelled, System::SharedPtr<Object> userState, System::ArrayPtr<System::SharedPtr<Object>> results)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| error | [Exception](../../../system/exception/) | 在非同步操作期間發生的任何錯誤。 |
| cancelled | **bool** | 指示非同步操作是否已取消的值。 |
| userState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 傳遞給 [System.ComponentModel.BackgroundWorker.RunWorkerAsync](../../../system.componentmodel/backgroundworker/runworkerasync/)([System.Object](../../../system/object/)) 方法的可選使用者提供之狀態物件。 |
| results | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | 非同步操作結果的集合。 |

## 參見

* 型別別名 [Exception](../../../system/exception/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [Object](../../../system/object/)
* 類別 [InvokeCompletedEventArgs](../)
* 命名空間 [System::Web::Services::Protocols](../../)
* 函式庫 [Aspose.Slides](../../../)