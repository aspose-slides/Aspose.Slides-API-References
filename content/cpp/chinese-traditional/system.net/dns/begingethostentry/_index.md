---
title: BeginGetHostEntry()
second_title: Aspose.Slides for C++ API 參考文件
description: 啟動非同步操作，以使用包含主機名稱或 IP 位址的指定字串建立新的 IPHostEntry-class 實例。
type: docs
weight: 105
url: /zh-hant/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) 方法

啟動非同步操作，以使用包含主機名稱或 IP 位址的字串建立新的 IPHostEntry-class 實例。

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | 包含主機名稱或 IP 位址的字串。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 當操作完成時要呼叫的回呼函式。 |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步操作。 |

### 返回值

表示已啟動非同步操作的 [IAsyncResult](../../../system/iasyncresult/) 物件。

## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) 方法

啟動非同步操作，以使用指定的 IP 位址建立新的 IPHostEntry-class 實例。

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP 位址。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 當操作完成時要呼叫的回呼函式。 |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步操作。 |

### 返回值

表示已啟動非同步操作的 [IAsyncResult](../../../system/iasyncresult/) 物件。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 型別定義 [AsyncCallback](../../../system/asynccallback/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [String](../../../system/string/)
* 類別 [Object](../../../system/object/)
* 類別 [Dns](../)
* 類別 [IPAddress](../../ipaddress/)
* 命名空間 [System::Net](../../)
* 函式庫 [Aspose.Slides](../../../)