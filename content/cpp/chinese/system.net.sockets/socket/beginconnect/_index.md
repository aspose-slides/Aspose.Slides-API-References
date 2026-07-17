---
title: BeginConnect()
second_title: Aspose.Slides for C++ API 参考
description: 启动异步连接操作。
type: docs
weight: 573
url: /zh/system.net.sockets/socket/beginconnect/
---
## Socket::BeginConnect(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) 方法

启动异步连接操作。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<EndPoint> remoteEP, AsyncCallback callback, System::SharedPtr<Object> state)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 远程端点。 |
| callback | [AsyncCallback](../../../system/asynccallback/) | 当操作完成时将调用的回调。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用户提供的数据，用于唯一标识每个异步连接操作。 |

### 返回值

一个[IAsyncResult](../../../system/iasyncresult/)对象，表示已启动的异步连接操作。

## Socket::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 方法

启动异步连接操作。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| host | [String](../../../system/string/) | 远程主机名。 |
| port | **int32_t** | 远程主机的端口号。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 当操作完成时将调用的回调。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用户提供的数据，用于唯一标识每个异步连接操作。 |

### 返回值

一个[IAsyncResult](../../../system/iasyncresult/)对象，表示已启动的异步连接操作。

## Socket::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 方法

启动异步连接操作。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | 远程主机的 IP 地址。 |
| port | **int32_t** | 远程主机的端口号。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 当操作完成时将调用的回调。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用户提供的数据，用于唯一标识每个异步连接操作。 |

### 返回值

一个[IAsyncResult](../../../system/iasyncresult/)对象，表示已启动的异步连接操作。

## Socket::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) 方法

启动异步连接操作。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | 远程主机的 IP 地址列表。 |
| port | **int32_t** | 远程主机的端口号。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 当操作完成时将调用的回调。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用户提供的数据，用于唯一标识每个异步连接操作。 |

### 返回值

一个[IAsyncResult](../../../system/iasyncresult/)对象，表示已启动的异步连接操作。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [AsyncCallback](../../../system/asynccallback/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [EndPoint](../../../system.net/endpoint/)
* 类 [Object](../../../system/object/)
* 类 [Socket](../)
* 类 [String](../../../system/string/)
* 类 [IPAddress](../../../system.net/ipaddress/)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)