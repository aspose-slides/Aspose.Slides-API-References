---
title: BeginGetHostByName()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的主機名稱，啟動非同步操作以建立新的 IPHostEntry-class 實例。
type: docs
weight: 53
url: /zh-hant/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName(String, AsyncCallback, System::SharedPtr\<Object\>) 方法

使用指定的主機名稱，啟動非同步操作以建立新的 IPHostEntry-class 實例。

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | 主機名稱。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 當操作完成時要呼叫的回呼。 |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一標識每個非同步操作。 |

### 返回值

一個 [IAsyncResult](../../../system/iasyncresult/) 物件，表示已啟動的非同步操作。

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類型定義 [AsyncCallback](../../../system/asynccallback/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [String](../../../system/string/)
* 類別 [Object](../../../system/object/)
* 類別 [Dns](../)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)