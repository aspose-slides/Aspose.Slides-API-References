---
title: BeginConnect()
second_title: Aspose.Slides for C++ API 參考
description: 啟動非同步連線作業。
type: docs
weight: 261
url: /zh-hant/system.net.sockets/tcpclient/beginconnect/
---
## TcpClient::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 方法

啟動非同步連線作業。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| host | [String](../../../system/string/) | 遠端主機名稱。 |
| port | **int32_t** | 遠端主機的埠號。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 操作完成時將被呼叫的回呼。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步連線作業。 |

### 回傳值

一個 [IAsyncResult](../../../system/iasyncresult/) 物件，表示已啟動的非同步連線作業。

## TcpClient::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 方法

啟動非同步連線作業。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | 遠端主機的 IP 位址。 |
| port | **int32_t** | 遠端主機的埠號。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 操作完成時將被呼叫的回呼。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步連線作業。 |

### 回傳值

一個 [IAsyncResult](../../../system/iasyncresult/) 物件，表示已啟動的非同步連線作業。

## TcpClient::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 方法

啟動非同步連線作業。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | 遠端主機的 IP 位址。 |
| port | **int32_t** | 遠端主機的埠號。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 操作完成時將被呼叫的回呼。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步連線作業。 |

### 回傳值

一個 [IAsyncResult](../../../system/iasyncresult/) 物件，表示已啟動的非同步連線作業。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [String](../../../system/string/)
* 類別 [Object](../../../system/object/)
* 類別 [TcpClient](../)
* 類別 [IPAddress](../../../system.net/ipaddress/)
* 命名空間 [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)