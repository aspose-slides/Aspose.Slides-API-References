---
title: BeginConnect()
second_title: Aspose.Slides for C++ API 参考
description: 发起一次异步连接操作。
type: docs
weight: 261
url: /zh/system.net.sockets/tcpclient/beginconnect/
---
## TcpClient::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 方法

发起一次异步连接操作。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | 远程主机名。 |
| port | **int32_t** | 远程主机的端口。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 当操作完成时将被调用的回调。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用于唯一标识每个异步连接操作的用户提供数据。 |

### 返回值

一个表示已启动的异步连接操作的 [IAsyncResult](../../../system/iasyncresult/) 对象。

## TcpClient::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 方法

发起一次异步连接操作。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | 远程主机的 IP 地址。 |
| port | **int32_t** | 远程主机的端口。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 当操作完成时将被调用的回调。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用于唯一标识每个异步连接操作的用户提供数据。 |

### 返回值

一个表示已启动的异步连接操作的 [IAsyncResult](../../../system/iasyncresult/) 对象。

## TcpClient::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 方法

发起一次异步连接操作。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | 远程主机的 IP 地址集合。 |
| port | **int32_t** | 远程主机的端口。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 当操作完成时将被调用的回调。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用于唯一标识每个异步连接操作的用户提供数据。 |

### 返回值

一个表示已启动的异步连接操作的 [IAsyncResult](../../../system/iasyncresult/) 对象。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [AsyncCallback](../../../system/asynccallback/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [String](../../../system/string/)
* 类 [Object](../../../system/object/)
* 类 [TcpClient](../)
* 类 [IPAddress](../../../system.net/ipaddress/)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)