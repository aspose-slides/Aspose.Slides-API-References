---
title: BeginGetHostEntry()
second_title: Aspose.Slides for C++ API 参考
description: 启动一个异步操作，以使用包含主机名或 IP 地址的指定字符串创建一个新的 IPHostEntry-class 实例。
type: docs
weight: 105
url: /zh/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) method

启动一个异步操作，以使用包含主机名或 IP 地址的指定字符串创建一个新的 IPHostEntry-class 实例。

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | 包含主机名或 IP 地址的字符串。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 当操作完成时调用的回调。 |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用户提供的数据，用于唯一标识每个异步操作。 |

### 返回值

一个表示已启动的异步操作的 [IAsyncResult](../../../system/iasyncresult/) 对象。

## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) method

启动一个异步操作，以使用指定的 IP 地址创建一个新的 IPHostEntry-class 实例。

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP 地址。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 当操作完成时调用的回调。 |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 用户提供的数据，用于唯一标识每个异步操作。 |

### 返回值

一个表示已启动的异步操作的 [IAsyncResult](../../../system/iasyncresult/) 对象。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [AsyncCallback](../../../system/asynccallback/)
* 类 [IAsyncResult](../../../system/iasyncresult/)
* 类 [String](../../../system/string/)
* 类 [Object](../../../system/object/)
* 类 [Dns](../)
* 类 [IPAddress](../../ipaddress/)
* 命名空间 [System::Net](../../)
* 库 [Aspose.Slides](../../../)