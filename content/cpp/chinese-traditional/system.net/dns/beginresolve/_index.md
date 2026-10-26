---
title: BeginResolve()
second_title: Aspose.Slides for C++ API 參考文件
description: 啟動一個非同步操作，以使用指定的主機名稱建立新的 IPHostEntry-class 實例。
type: docs
weight: 157
url: /zh-hant/system.net/dns/beginresolve/
---
## Dns::BeginResolve(String, AsyncCallback, System::SharedPtr\<Object\>) 方法

啟動一個非同步操作，以使用指定的主機名稱建立新的 IPHostEntry 類別實例。

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | 用於建立 [IPHostEntry](../../iphostentry/) 類別新實例的主機名稱。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 當操作完成時將被呼叫的回呼函式。 |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步操作。 |

### 返回值

代表已啟動之非同步操作的 [IAsyncResult](../../../system/iasyncresult/) 物件。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 型別定義 [AsyncCallback](../../../system/asynccallback/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [String](../../../system/string/)
* 類別 [Object](../../../system/object/)
* 類別 [Dns](../)
* 名稱空間 [System::Net](../../)
* 程式庫 [Aspose.Slides](../../../)