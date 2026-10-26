---
title: BeginConnect()
second_title: Aspose.Slides for C++ API 參考
description: 啟動非同步連線作業。
type: docs
weight: 573
url: /zh-hant/system.net.sockets/socket/beginconnect/
---
## Socket::BeginConnect(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) 方法

啟動非同步連線作業。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<EndPoint> remoteEP, AsyncCallback callback, System::SharedPtr<Object> state)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 遠端端點。 |
| callback | [AsyncCallback](../../../system/asynccallback/) | 在操作完成時將被呼叫的 callback。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步連線作業。 |

### 返回值

一個表示已啟動非同步連線作業的 [IAsyncResult](../../../system/iasyncresult/) 物件。

## Socket::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 方法

啟動非同步連線作業。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| host | [String](../../../system/string/) | 遠端主機名稱。 |
| port | **int32_t** | 遠端主機的埠號。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 在操作完成時將被呼叫的 callback。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步連線作業。 |

### 返回值

一個表示已啟動非同步連線作業的 [IAsyncResult](../../../system/iasyncresult/) 物件。

## Socket::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 方法

啟動非同步連線作業。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | 遠端主機的 IP 位址。 |
| port | **int32_t** | 遠端主機的埠號。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 在操作完成時將被呼叫的 callback。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步連線作業。 |

### 返回值

一個表示已啟動非同步連線作業的 [IAsyncResult](../../../system/iasyncresult/) 物件。

## Socket::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 方法

啟動非同步連線作業。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | 遠端主機的 IP 位址。 |
| port | **int32_t** | 遠端主機的埠號。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 在操作完成時將被呼叫的 callback。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 使用者提供的資料，用於唯一識別每個非同步連線作業。 |

### 返回值

一個表示已啟動非同步連線作業的 [IAsyncResult](../../../system/iasyncresult/) 物件。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [AsyncCallback](../../../system/asynccallback/)
* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [IAsyncResult](../../../system/iasyncresult/)
* 類別 [EndPoint](../../../system.net/endpoint/)
* 類別 [Object](../../../system/object/)
* 類別 [Socket](../)
* 類別 [String](../../../system/string/)
* 類別 [IPAddress](../../../system.net/ipaddress/)
* 命名空間 [System::Net::Sockets](../../)
* 函式庫 [Aspose.Slides](../../../)